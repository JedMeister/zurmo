Zurmo - Gamified, Social, Mobile CRM system
===========================================

`Zurmo`_ is an open source CRM application that is mobile, social, and
gamified. It aims to provide an easy-to-use, easy-to-customize CRM
application that can be adapted to any business use case. Zurmo is
carefully designed and tested such that future updates will not break
your customized CRM installation.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Zurmo configurations:
   
    - Installed from upstream source code to /var/www/zurmo
    - Includes and configured to use Memcached (recommended for
      production).

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Supervised Manual Zurmo Update
-------------------------------------------

To upgrade to the latest version of Zurmo see `Upgrades`_ on the
Zurmo website.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL: username **root**
-  Adminer: username **adminer**
-  Zurmo: username **admin**


.. _Zurmo: http://zurmo.org/
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org/
.. _Upgrades: http://zurmo.org/upgrades

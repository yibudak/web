===================
Drop target support
===================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:726d388b710527c7eb27a6eaf3973c253d90811132df8910cfe228afd0ade7db
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fweb-lightgray.png?logo=github
    :target: https://github.com/OCA/web/tree/12.0/web_drop_target
    :alt: OCA/web
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/web-12-0/web-12-0-web_drop_target
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/web&target_branch=12.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module extends the functionality of the web client to support dropping local files into the web client.

By default, an attachment will be created when dropping a file on a form.

Further, this module is meant as a base drag&drop module supporting other actions after some file is dropped so that other modules can add more features.

**Table of contents**

.. contents::
   :local:

Usage
=====

To use this module, you need to:

#. drag a file from your local computer onto an Odoo form view
#. it should become an attachment of the currently opened record

.. image:: https://raw.githubusercontent.com/web_drop_target/static/description/screenshot.png
    :alt: Screenshot

Development
===========

**Libraries**

* `base64js <https://raw.githubusercontent.com/beatgammit/base64-js>`_.

Known issues / Roadmap
======================

* dropping on list or kanban views would be nice too
* handle multiple files
* add an upload progress meter for huge files
* trigger custom events about different stages of the drop operation for other addons to hook in
* Install document module to display attachments in the sidebar

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/web/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/web/issues/new?body=module:%20web_drop_target%0Aversion:%2012.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Therp BV

Contributors
~~~~~~~~~~~~

* Holger Brunn <hbrunn@therp.nl>
* Pablo Fuentes <pablo@studio73.es>
* Akim Juillerat <akim.juillerat@camptocamp.com>
* Enric Tobella <etobella@creublanca.es>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/web <https://github.com/OCA/web/tree/12.0/web_drop_target>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.

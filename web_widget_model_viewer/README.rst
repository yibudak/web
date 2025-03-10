===================
Model viewer widget
===================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:ca7d5c0a1779e4d1d38d693b1fd07fb818a137abf3aef200005d08061472576b
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fweb-lightgray.png?logo=github
    :target: https://github.com/OCA/web/tree/12.0/web_widget_model_viewer
    :alt: OCA/web
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/web-12-0/web-12-0-web_widget_model_viewer
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/web&target_branch=12.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

``<model-viewer>`` is a web component that makes rendering interactive 3D models - optionally in AR - easy to do, on as many browsers and devices as possible. ``<model-viewer>`` strives to give you great defaults for rendering quality and performance.

See `source repository <https://github.com/google/model-viewer>`_ and `documentation <https://modelviewer.dev/>`_.

The model to load is a GLTF 2.0 file format.

See `<https://www.khronos.org/gltf/>`_ and GLTF overview:

.. figure:: https://raw.githubusercontent.com/OCA/web/12.0/web_widget_model_viewer/static/img/gltfOverview.png

Many engine developers have already started transitioning to glTF 2.0 to reap performance, portability and quality benefits, including BabylonJS, three.js, Cesium, Sketchfab, and xeogl and instant3Dhub engines. glTF 2.0 is also seeing industry support by companies such as Adobe, Google, Marmoset, Microsoft, NVIDIA, Oculus, UX3D, and more as well as prominent universities such as, University of Pennsylvania and Sapienza University of Rome.

"example" directory contains the GLB file of a chair, that is rendered in the following way:

.. figure:: https://raw.githubusercontent.com/OCA/web/12.0/web_widget_model_viewer/static/img/Eames_Lounge_Chair.gif

**Table of contents**

.. contents::
   :local:

Usage
=====

Add ``widget="model_viewer"`` to your binary field in form view. Optionally you can set ``style`` and ``max_upload_size`` (in MB) attributes.

Changelog
=========

12.0.2.0.0 (2020-07-14)
~~~~~~~~~~~~~~~~~~~~~~~

* [IMP] fullscreen and view redesign

12.0.1.0.0 (2020-07-10)
~~~~~~~~~~~~~~~~~~~~~~~

* Start of the history.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/web/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/web/issues/new?body=module:%20web_widget_model_viewer%0Aversion:%2012.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* TAKOBI
* Openindustry.it

Contributors
~~~~~~~~~~~~

* Lorenzo Battistini (https://takobi.online)
* Andrea Piovesana (https://openindustry.it)

Other credits
~~~~~~~~~~~~~

Chair © Copyright 2020 Shopify Inc., licensed under CC-BY-4.0.

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-eLBati| image:: https://github.com/eLBati.png?size=40px
    :target: https://github.com/eLBati
    :alt: eLBati

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-eLBati| 

This module is part of the `OCA/web <https://github.com/OCA/web/tree/12.0/web_widget_model_viewer>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.

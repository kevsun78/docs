ODK Cloud Endpoints
===============================

.. _cloud-endpoints-intro:

:dfn:`ODK Cloud Endpoints` are servers that communicate with the ODK-X Android applications. They implement the `ODK-X REST Protocol <https://github.com/opendatakit/opendatakit/wiki/ODK-2.0-Synchronization-API-(RESTful)>`_.

There are currently two options for Cloud Endpoints to communicate with ODK-X tools.

  - :doc:`sync-endpoint` - Supports the full ODK-X REST Protocol
  - :doc:`aggregate-tables-extension` - Supports the majority of the ODK-X REST Protocol; however, is missing group permission filtering support.

.. _cloud-endpoints_intro_sys-admin-guide:

System Administrator Guide
---------------------------

.. toctree::

  sync-endpoint
  aggregate-tables-extension


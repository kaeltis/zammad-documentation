Welcome to Zammad's documentation!
==================================
The Zammad documentation consists of three parts:

- Zammad system installation and configuration (this documentation)

- Zammad administration (https://admin-docs.zammad.org)

- Zammad user documentation (https://user-docs.zammad.org)

.. toctree::
   :maxdepth: 2
   :caption: About

   /about/zammad


.. toctree::
   :maxdepth: 2
   :caption: Prerequisites

   /prerequisites/software
   /prerequisites/hardware


.. toctree::
   :maxdepth: 1
   :caption: Installation & Update

   /install/package
   /install/source
   /install/elasticsearch
   /install/docker-compose
   /install/kubernetes
   /install/univention
   /install/update


.. toctree::
   :maxdepth: 2
   :caption: Getting started

   /getting-started/configure-webserver
   /getting-started/first-steps


.. toctree::
   :maxdepth: 1
   :caption: Migration

   /migration/index


.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Administration via ...

   Web-UI <https://admin-docs.zammad.org/>
   Console </admin/console>


.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Contributing / Development

   /contributing/start
   /contributing/branches
   /contributing/packages
   /contributing/ci
   /contributing/code-quality
   /contributing/install-docker
   /contributing/install-vagrant


.. toctree::
   :maxdepth: 2
   :glob:
   :caption: REST API

   /api/intro
   /api/user
   /api/organization
   /api/group
   /api/ticket
   /api/ticket-state
   /api/ticket-priority
   /api/ticket-article
   /api/notification
   /api/object
   /api/tags
   /api/user-access-token


.. toctree::
   :maxdepth: 2
   :glob:
   :caption: CTI API

   /cti/api-intro
   /cti/api-push


.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Appendix


   /appendix/backup-and-restore
   /appendix/configure-env-vars
   /appendix/configure-database-server
   /appendix/privacy
   /appendix/single-sign-on
   /appendix/troubleshooting
   /appendix/reporting-tools-thirdparty

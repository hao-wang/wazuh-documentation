.. Copyright (C) 2021 Wazuh, Inc.

.. code-block:: console

  # curl -so /etc/kibana/kibana.yml https://packages.wazuh.com/resources/4.2/elastic-stack/kibana/7.x/kibana_all_in_one.yml

Edit the ``/etc/kibana/kibana.yml`` file:

.. code-block:: yaml

    elasticsearch.password: <elasticsearch_password>

Values to be replaced:

- ``<elasticsearch_password>``: the password generated during the Elasticsearch installation and configuration for the ``elastic`` user.

.. End of configure_kibana.rst

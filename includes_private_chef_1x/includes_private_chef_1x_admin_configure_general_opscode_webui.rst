.. The contents of this file may be included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


This configuration file has the following settings for the |service webui| service:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Setting
     - Description
   * - ``opscode_webui['backlog']``
     - Default value: ``1024``. For example:

       .. code-block:: ruby

          opscode_webui['backlog'] = 1024

   * - ``opscode_webui['cookie_domain']``
     - Default value: ``"all"``. For example:

       .. code-block:: ruby

          opscode_webui['cookie_domain'] = "all"

   * - ``opscode_webui['cookie_secret']``
     - Default value: ``"47b3b8d95dea455baf32155e95d1e64e"``. For example:

       .. code-block:: ruby

          opscode_webui['cookie_secret'] = "47b3b8d95dea455baf32155e95d1e64e"

   * - ``opscode_webui['dir']``
     - Default value: ``"/var/opt/opscode/opscode-webui"``. For example:

       .. code-block:: ruby

          opscode_webui['dir'] = "/var/opt/opscode/opscode-webui"

   * - ``opscode_webui['enable']``
     - |enable service| Default value: ``true``. For example:

       .. code-block:: ruby

          opscode_webui['enable'] = true

   * - ``opscode_webui['environment']``
     - Default value: ``"privatechef"``. For example:

       .. code-block:: ruby

          opscode_webui['environment'] = "privatechef"

   * - ``opscode_webui['ha']``
     - |use ha| Default value: ``false``. For example:

       .. code-block:: ruby

          opscode_webui['ha'] = false

   * - ``opscode_webui['listen']``
     - Default value: ``"127.0.0.1:9462"``. For example:

       .. code-block:: ruby

          opscode_webui['listen'] = "127.0.0.1:9462"

   * - ``opscode_webui['log_directory']``
     - |directory logs| The default value is the recommended value. Default value: ``"/var/log/opscode/opscode-webui"``. For example:

       .. code-block:: ruby

          opscode_webui['log_directory'] = "/var/log/opscode/opscode-webui"

   * - ``opscode_webui['port']``
     - |port opscode_webui| Default value: ``9462``. For example:

       .. code-block:: ruby

          opscode_webui['port'] = 9462

   * - ``opscode_webui['session_key']``
     - Default value: ``"_sandbox_session"``. For example:

       .. code-block:: ruby

          opscode_webui['session_key'] = "_sandbox_session"

   * - ``opscode_webui['svlogd_num']``
     - |svlogd_num| Default value: ``10``. For example:

       .. code-block:: ruby

          opscode_webui['svlogd_num'] = 10

   * - ``opscode_webui['svlogd_size']``
     - |svlogd_size| Default value: ``1000000``. For example:

       .. code-block:: ruby

          opscode_webui['svlogd_size'] = 1000000

   * - ``opscode_webui['tcp_nodelay']``
     - Default value: ``true``. For example:

       .. code-block:: ruby

          opscode_webui['tcp_nodelay'] = true

   * - ``opscode_webui['umask']``
     - |umask| Default value: ``"0022"``. For example:

       .. code-block:: ruby

          opscode_webui['umask'] = "0022"

   * - ``opscode_webui['url']``
     - Default value: ``"http://127.0.0.1:9462"``. For example:

       .. code-block:: ruby

          opscode_webui['url'] = "http://127.0.0.1:9462"

   * - ``opscode_webui['validation_client_name']``
     - |webui validation_client_name| Default value: ``"chef"``. For example:

       .. code-block:: ruby

          opscode_webui['validation_client_name'] = "chef"

   * - ``opscode_webui['vip']``
     - |ip_address virtual| Default value: ``"127.0.0.1"``. For example:

       .. code-block:: ruby

          opscode_webui['vip'] = "127.0.0.1"

   * - ``opscode_webui['worker_processes']``
     - |worker_processes| Default value: ``4``. For example:

       .. code-block:: ruby

          opscode_webui['worker_processes'] = 4

   * - ``opscode_webui['worker_timeout']``
     - |timeout worker| Default value: ``3600``. For example:

       .. code-block:: ruby

          opscode_webui['worker_timeout'] = 3600


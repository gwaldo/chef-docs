.. The contents of this file may be included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


This configuration file has the following settings for |nagios|:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Setting
     - Description
   * - ``nagios['admin_email']``
     - Default value: ``"nobody@example.com"``. For example:

       .. code-block:: ruby

          nagios['admin_email'] = "nobody@example.com"

   * - ``nagios['admin_pager']``
     - Default value: ``"nobody@example.com"``. For example:

       .. code-block:: ruby

          nagios['admin_pager'] = "nobody@example.com"

   * - ``nagios['admin_password']``
     - Default value: ``"privatechef"``. For example:

       .. code-block:: ruby

          nagios['admin_password'] = "privatechef"

   * - ``nagios['admin_user']``
     - Default value: ``"nagiosadmin"``. For example:

       .. code-block:: ruby

          nagios['admin_user'] = "nagiosadmin"

   * - ``nagios['alert_email']``
     - This setting requires ``/usr/bin/mail``. Default value: ``"nobody@example.com"``. For example:

       .. code-block:: ruby

          nagios['alert_email'] = "nobody@example.com"

   * - ``nagios['debug_level']``
     - Default value: ``0``. For example:

       .. code-block:: ruby

          nagios['debug_level'] = 0

   * - ``nagios['debug_verbosity']``
     - Default value: ``1``. For example:

       .. code-block:: ruby

          nagios['debug_verbosity'] = 1

   * - ``nagios['default_host']``
     - Default value:

       .. code-block:: ruby

          {"check_interval"=>15,
           "retry_interval"=>15,
           "max_check_attempts"=>1,
           "notification_interval"=>300}

       For example:

       .. code-block:: ruby

          nagios['default_host'] = {"check_interval"=>15,
                                    "retry_interval"=>15,
                                    "max_check_attempts"=>1,
                                    "notification_interval"=>300}
   * - ``nagios['default_service']``
     - Default value:

       .. code-block:: ruby

          {"check_interval"=>60,
           "retry_interval"=>15,
           "max_check_attempts"=>3,
           "notification_interval"=>1200}

       For example:

       .. code-block:: ruby

          nagios['default_service'] = {"check_interval"=>60,
                                       "retry_interval"=>15,
                                       "max_check_attempts"=>3,
                                       "notification_interval"=>1200}

   * - ``nagios['dir']``
     - Default value: ``"/var/opt/opscode/nagios"``. For example:

       .. code-block:: ruby

          nagios['dir'] = "/var/opt/opscode/nagios"

   * - ``nagios['enable']``
     - |enable service| Default value: ``true``. For example:

       .. code-block:: ruby

          nagios['enable'] = true

   * - ``nagios['fcgiwrap_log_directory']``
     - Default value: ``"/var/log/opscode/fcgiwrap"``. For example:

       .. code-block:: ruby

          nagios['fcgiwrap_log_directory'] = "/var/log/opscode/fcgiwrap"


   * - ``nagios['fcgiwrap_svlogd_size']``
     - For the svlogd-managed 'current' log set a rotation policy based on the size, in bytes, of the logfile. Default value: ``1000000``. For example:

       .. code-block:: ruby

          nagios['fcgiwrap_svlogd_size'] = 1000000


   * - ``nagios['fcgiwrap_svlogd_num']``
     - For the svlogd-managed 'current' log set a retention policy based on the number of logfiles retained. Default value: ``10``. For example:

       .. code-block:: ruby

          nagios['fcgiwrap_svlogd_num'] = 10

   * - ``nagios['fcgiwrap_port']``
     - Default value: ``9670``. For example:

       .. code-block:: ruby

          nagios['fcgiwrap_port'] = 9670

   * - ``nagios['ha']``
     - |use ha| Default value: ``false``. For example:

       .. code-block:: ruby

          nagios['ha'] = false

   * - ``nagios['hosts']``
     - Default value: ``{"ubuntu"=>{"ipaddress"=>"192.168.4.131", "hostgroups"=>[]}}``. For example:

       .. code-block:: ruby

          nagios['hosts'] = {
            "ubuntu"=>{
              "ipaddress"=>"192.168.4.131", "hostgroups"=>[]
            }
          }

   * - ``nagios['interval_length']``
     - Default value: ``1``. For example:

       .. code-block:: ruby

          nagios['interval_length'] = 1

   * - ``nagios['log_directory']``
     - |directory logs| The default value is the recommended value. Default value: ``"/var/log/opscode/nagios"``. For example:

       .. code-block:: ruby

          nagios['log_directory'] = "/var/log/opscode/nagios"

   * - ``nagios['php_fpm_log_directory']``
     - Default value: ``"/var/log/opscode/php-fpm"``. For example:

       .. code-block:: ruby

          nagios['php_fpm_log_directory'] = "/var/log/opscode/php-fpm"

   * - ``nagios['php_fpm_svlogd_num']``
     - |svlogd_num| Default value: ``10``. For example:

       .. code-block:: ruby

          nagios['php_fpm_svlogd_num'] = 10

   * - ``nagios['php_fpm_svlogd_size']``
     - |svlogd_size| Default value: ``1000000``. For example:

       .. code-block:: ruby

          nagios['php_fpm_svlogd_size'] = 1000000

   * - ``nagios['php_fpm_port']``
     - Default value: ``9000``. For example:

       .. code-block:: ruby

          nagios['php_fpm_port'] = 9000

   * - ``nagios['port']``
     - Default value: ``9671``. For example:

       .. code-block:: ruby

          nagios['port'] = 9671

   * - ``nagios['svlogd_num']``
     - |svlogd_num| Default value: ``10``. For example:

       .. code-block:: ruby

          nagios['svlogd_num'] = 10

   * - ``nagios['svlogd_size']``
     - |svlogd_size| Default value: ``1000000``. For example:

       .. code-block:: ruby

          nagios['svlogd_size'] = 1000000


.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

|description resource_attributes_intro|

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Attribute
     - Description
   * - ``chef_server``
     - |chef_server_url|
   * - ``clients``
     - 
   * - ``complete``
     - Use to specify if this resource defines a |chef client| completely. When ``true``, any attribute not specified by this resource will be reset to default attribute values.
   * - ``groups``
     - 
   * - ``name``
     - 
   * - ``raw_json``
     - The group as |json| data. For example:
       
       .. code-block:: javascript
       
          {
	        :groupname => "chef"
          }
   * - ``remove_clients``
     - 
   * - ``remove_groups``
     - 
   * - ``remove_users``
     - 
   * - ``users``
     - 


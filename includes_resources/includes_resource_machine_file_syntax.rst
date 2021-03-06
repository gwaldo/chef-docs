.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

The syntax for using the |resource machine_file| resource in a recipe is as follows:

.. code-block:: ruby

   machine_file "name" do
     attribute "value" # see attributes section below
     ...
     action :action # see actions section below
   end

where 

* ``machine_file`` tells the |chef client| to use the ``Chef::Provider::MachineFile`` provider during the |chef client| run
* ``name`` is the name of the resource block; when the ``path`` attribute is not specified as part of a recipe, ``name`` is also the path to a file
* ``attribute`` is zero (or more) of the attributes that are available for this resource
* ``:action`` identifies which steps the |chef client| will take to bring the node into the desired state

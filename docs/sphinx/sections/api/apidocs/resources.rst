.. currentmodule:: dagster

Resources
=========

Pythonic resource system
------------------------

The following classes are used as part of the new `Pythonic resources system </concepts/resources>`_.


.. autoclass:: ConfigurableResource

.. autoclass:: ResourceDefinition
    :members: hardcoded_resource, mock_resource, none_resource, configured

.. autoclass:: InitResourceContext
    :members:

.. autofunction:: make_values_resource

.. autofunction:: build_init_resource_context

.. autofunction:: build_resources

.. autofunction:: with_resources

Legacy resource system
----------------------

The following classes are used as part of the `legacy resource system </concepts/resources-legacy>`_.


.. autodecorator:: resource

.. currentmodule:: dagster

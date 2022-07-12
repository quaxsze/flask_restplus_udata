.. _api:

API
===

.. currentmodule:: flask_restplus_udata

Core
----

.. autoclass:: Api
    :members:
    :inherited-members:

.. autoclass:: Namespace
    :members:


.. autoclass:: Resource
    :members:
    :inherited-members:


Models
------

.. autoclass:: flask_restplus_udata.Model
    :members:

All fields accept a ``required`` boolean and a ``description`` string in ``kwargs``.

.. automodule:: flask_restplus_udata.fields
    :members:


Serialization
-------------
.. currentmodule:: flask_restplus_udata

.. autofunction:: marshal

.. autofunction:: marshal_with

.. autofunction:: marshal_with_field

.. autoclass:: flask_restplus_udata.mask.Mask
    :members:

.. autofunction:: flask_restplus_udata.mask.apply


Request parsing
---------------

.. automodule:: flask_restplus_udata.reqparse
    :members:

Inputs
~~~~~~

.. automodule:: flask_restplus_udata.inputs
    :members:


Errors
------

.. automodule:: flask_restplus_udata.errors
    :members:

.. autoexception:: flask_restplus_udata.fields.MarshallingError

.. autoexception:: flask_restplus_udata.mask.MaskError

.. autoexception:: flask_restplus_udata.mask.ParseError


Schemas
-------

.. automodule:: flask_restplus_udata.schemas
    :members:


Internals
---------

These are internal classes or helpers.
Most of the time you shouldn't have to deal directly with them.

.. autoclass:: flask_restplus_udata.api.SwaggerView

.. autoclass:: flask_restplus_udata.swagger.Swagger

.. autoclass:: flask_restplus_udata.postman.PostmanCollectionV1

.. automodule:: flask_restplus_udata.utils
    :members:

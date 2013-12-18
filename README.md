Bizowie-API-py
=================

These are python bindings for the Bizowie [cloud ERP](http://bizowie.com/solutions/).

Please feel free to fork this repository and patch it.

#### Example usage of module:

> import Bizowie.API 

> apibz = Bizowie.API.API("somesite.site"), "key", "private\_key")

> apibz.call('database/update/1/1003', { 'name':'steve' } ) 


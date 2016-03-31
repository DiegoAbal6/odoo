

Tutorial y documentacion sobre Odoo: https://www.odoo.com/documentation/8.0/howtos/backend.html

Github seguido para poder acabar el trabajo: https://github.com/damiannogueiras/moduloOdoo

####

**Creación del módulo de Odoo**

Accedemos a Netbeans y creamos un proyecto llamado "Odoo" por ejemplo.

El siguiente paso sera crear una carpeta que se llame "openacademy", dentro del proyecto creado.

##

**Comenzamos**

Los siguientes pasos se harán dentro de la carpeta "openacademy":

**1)**

    Creamos una carpeta llamada controllers y dentro de ella, dos ficheros, que contendrán lo siguiente:

    **__init__.py**

```java
# -*- coding: utf-8 -*-

from . import controllers
```
    **controllers.py**

```java

# -*- coding: utf-8 -*-
from openerp import http

# class Openacademy(http.Controller):
#     @http.route('/openacademy/openacademy/', auth='public')
#     def index(self, **kw):
#         return "Hola"

#     @http.route('/openacademy/openacademy/objects/', auth='public')
#     def list(self, **kw):
#         return http.request.render('openacademy.listing', {
#             'root': '/openacademy/openacademy',
#             'objects': http.request.env['openacademy.openacademy'].search([]),
#         })

#     @http.route('/openacademy/openacademy/objects/<model("openacademy.openacademy"):obj>/', auth='public')
#     def object(self, obj, **kw):
#         return http.request.render('openacademy.object', {
#             'object': obj
#         })

```
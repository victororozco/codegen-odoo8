# codegen-odoo8
Generador de código para Dia adaptado a la versión 8 de odoo

# Pasos para la instalacion de codegen-odoo8 para Dia.

### Descarga del repositorio por medio de git

Abrir una terminal y ejecutar lo siguiente:

    $ git clone https://github.com/vijoin/codegen-odoo8.git

Nos vamos a la carpeta de codegen-odoo8

    $cd codegen-odoo8/

Como root copiamos el archivo a la carpeta de instalacion de Dia.

    # cp codegen_Odoov8.py /usr/share/dia/python

Abrimos dia y verificamos que esta correctamente instalado.

  1. Clic en Archivo > Exportar > Determinar Tipo de Archivo > PyDia Generador de Codigo (Odoo) (*.zip)

##Observaciones:
Al definir un One2many o un Many2many es necesario que la etiqueta (label) se especifique con el atributo string='etiqueta' pues codegen necesita convertir eso a un <separator />

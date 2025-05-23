=====================
Binaural Contabilidad
=====================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3

|badge1|

Este módulo agrega los campos de móneda alterna y tasa de cambio a ciertos modelos.
Estos son:

* Conciliación Parcial.

  * Tasa inversa del movimiento del debe.

  * Tasa inversa del movimiento del haber.

* Asiento Contable

  * Móneda Alterna.

  * Tasa.

  * Tasa Inversa.

  * Tasa Manual.

  * Identificación.

  * Documento Financiero.

  * Base Imponible Alterna.

  * Total Gravado.

  * Total Facturado Alterno.
  * Tasa Actualizada Manualmente.
* Apunte Contable.

  * Móneda Alterna.

  * Tasa.

  * Tasa Inversa.

  * Precio Alterno.

  * Subtotal Alterno.

  * Total Alterno.

  * Débito Alterno.

  * Crédito Alterno.

  * Balance Alterno.

  * Ajuste de Débito Alterno.

  * Ajuste de Crédito Alterno.

* Pagos.

  * Móneda Alterna.

  * Tasa.

  * Tasa Inversa.

Además, se agrega la funcionalidad para que los asientos de los pagos tengan
la tasa del pago en cuestión.

También se agregaron al wizard de pagos los siguientes campos:

* Móneda Alterna.
* Tasa.
* Tasa Inversa.


Validaciones
""""""""""""

* Los asientos contables ahora son únicos por número de secuencia, contacto, estado y diario.

Al momento de cambiar la tasa manualmente en la factura este manda un mensaje en el tracking para
saber la tasa anterior y la nueva tasa colocada


**Tabla de Contenidos**

.. contents::
   :local:

Créditos
========

Autor/es
~~~~~~~~

* Binauraldev

Mantenedor/es
~~~~~~~~~~~~~

Este módulo es mantenido por Binaural.

.. image:: https://binauraldev.com/wp-content/uploads/2022/01/logo-binaural.png
   :alt: Binaural dev
   :target: https://binauraldev.com/
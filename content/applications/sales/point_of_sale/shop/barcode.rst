========
Barcodes
========

Using a barcode scanner to process point-of-sale orders improves your efficiency in providing
quicker customer service.

Configuration
=============

To use a barcode scanner, you must first enable the feature in the Inventory app. To do so, go to
:menuselection:`Inventory --> Configuration --> Settings`, in the :guilabel:`Barcode` section, check
:guilabel:`Barcode Scanner` and save.

.. image:: barcode/barcode-inventory.png
   :align: center
   :alt: barcode setting in the Inventory application

.. seealso::
   - :doc:`Set up a barcode scanner<../../../inventory_and_mrp/inventory/barcode/setup/hardware>`
   - :doc:`Activate barcode scanners<../../../inventory_and_mrp/inventory/barcode/setup/software>`

Once enabled in **Inventory**, you can use the barcode feature in **Point of Sale** with products
that have a barcode number assigned.

Assign barcodes
===============

To your products
----------------

To use this feature in POS, your products must have barcodes assigned. To do so, go to
:menuselection:`Point of Sale --> Products --> Products` and select a product to open the **product
form**. In the :guilabel:`General Information` tab, add a barcode number in the :guilabel:`Barcode`
field.

To your employees
-----------------

To add an identification number to an employee, go to the **Employees** app, select an employee to
open the **employee form**, click :guilabel:`HR Settings` and type your employee identification
number in the :guilabel:`PIN Code` field.

Use barcodes
============

Scan a product's barcode using a barcode scanner. Doing so adds it  directly to the cart. To change
the quantity, scan a product as many times as needed or click :guilabel:`Qty` and enter the number
of products using the keypad.

You can also enter the barcode number manually in the search bar to look for the product. Then,
select it to add it to the cart.

.. seealso::
   - :doc:`Get started <../overview/getting_started>`

Log employees
-------------

You can also use a barcode scanner to log your employees. To do so, :ref:`restrict access
<restrict-employee-pos>` to the POS, set an :ref:`identification number <set-pin-code>` to your
employees, and :ref:`use barcodes to log your employees in <employee-barcode>` your POS.

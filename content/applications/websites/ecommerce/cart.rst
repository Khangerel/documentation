===========
Add to cart
===========

(introduction)

'Add to Cart' action customization
==================================

You can customize the main action of the :guilabel:`Add to Cart` button on the product page to also
perform one of the following actions:

- (Add to cart and) stay on the product page;
- (Add to cart and) redirect to the cart page;
- (Add to cart and) open a dialog box to let the user choose.

To configure the action button, go to :menuselection:`Configuration --> Settings --> Shop - Checkout
Process`, and select one of the three options in :guilabel:`Add to Cart`.

.. note::
   The action of the :guilabel:`Add to Cart` button is specific per website.

Hide the 'Add to Cart' button
=============================

If you do not need or wish to use the :guilabel:`Add to Cart` button, you can replace the button
with a :guilabel:`Contact Us` button which integrates a custom **redirect URL** of your choice.
When clicking on the :guilabel:`Contact Us` button, customers are taken to the page specified in the
settings.

To do so, go to :menuselection:`Configuration --> Settings --> Shop - Products` and tick
:guilabel:`Prevent Sale of Zero Priced Product`. This creates a new :guilabel:`Button url` field
where you can enter the **redirect URL** to be used. Then, set the price of the product to `0.00`
either from the **product's template**, or from a
:doc:`pricelist <../../../sales/sales/products_prices/prices/pricing>`.

.. tip::
   Hiding the :guilabel:`Add to Cart` button is often used by B2B eCommerces that need to restrict
   purchases to customers with an account, but still want to display an online product catalog.

.. image:: cart/variants-contactus.png
   :align: center
   :alt: Contact us button on product page

Custom 'Add to Cart' button
===========================

You can also create a **custom** :guilabel:`Add to Cart` button and link it to a specific product.
The

+ buy now
+ re-order from portal

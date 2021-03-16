---
title: Magento 2.4.0 known issue: Create New Order buttons missing
link: https://support.magento.com/hc/en-us/articles/360047481431-Magento-2-4-0-known-issue-Create-New-Order-buttons-missing
labels: Magento Commerce Cloud,Magento Commerce,order,known issues,products,SKU,button,2.4.0
---

This article provides a workaround for a known issue in Magento Admin for two missing buttons on the order creation page. When creating a new order for a new or existing customer, it is not possible to add products to the order from the catalog since the Add Products By SKU and Add Products buttons are missing. This is caused by JS bundling being enabled. A fix will be available in Magento 2.4.1. ## Affected products and versions

* Magento Commerce version 2.4.0
* Magento Commerce Cloud version 2.4.0

## Issue

Steps to reproduce

1. Go to Customers > All Customers.
1. Click the Edit link on a customer.
1. Click the Create Order button.

Expected result

The Add Products By SKU and Add Products buttons appear on the Create New Order page.

Actual result 

The Add Products By SKU and Add Products buttons are missing on the Create New Order page.

## Workaround

The workaround for this issue is to disable JS bundling for the Magento instance. The issue is expected to be fixed in Magento version 2.4.1, which is scheduled for release in Q4 1. ## Related reading

* [Magento 2.4.0 known issue: raw message data display on storefront](https://support.magento.com/hc/en-us/articles/360045804332)
* [Magento 2.4.0 known issue: Export Tax Rates does not work](https://support.magento.com/hc/en-us/articles/360045850032)
* [Magento 2.4.0 known issue: Braintree payment methods do not show up in Multiple Addresses checkout](https://support.magento.com/hc/en-us/articles/360046354992)
* [Magento 2.4.0 known issue: Error message selecting local payment method displayed for some countries during checkout](https://support.magento.com/hc/en-us/articles/360047139331-Magento-2-4-0-known-issue-Error-message-selecting-local-payment-method-displayed-for-some-countries-during-checkout)
* [Magento 2.4.0 known issue: 404 error when removing rewards points on multi-shipping checkout](https://support.magento.com/hc/en-us/articles/360046920131-Magento-2-4-0-known-issue-404-error-when-removing-rewards-points-on-multi-shipping-checkout)
* [Magento 2.4.0 known issue: orders display error](https://support.magento.com/hc/en-us/articles/360046802271-Magento-2-4-0-known-issue-orders-display-error)
* [Magento 2.4.0 B2B Admin can't add configurable product to quote](https://support.magento.com/hc/en-us/articles/360046801971-Magento-2-4-0-known-issue-B2B-Admin-cannot-add-a-configurable-product-to-a-quote)
* [Shipping labels creation known issue in Magento 2.4.0](https://support.magento.com/hc/en-us/articles/360046750171-Shipping-labels-creation-known-issue-in-Magento-2-4-0)
* [Magento 2.4.0 known issue - refresh on Customer's Activities does not work](https://support.magento.com/hc/en-us/articles/360046091332-Magento-2-4-0-known-issue-refresh-on-Customer-s-Activities-does-not-work)
* [Magento 2.4.0 known issue: “Add selections to my cart” button does not work](https://support.magento.com/hc/en-us/articles/360045838312-Magento-2-4-0-known-issue-Add-selections-to-my-cart-button-does-not-work)
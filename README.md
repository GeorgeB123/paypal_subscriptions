# paypal_subscriptions
PayPal Subscriptions for Commerce 2.x

This module contains:
- A payment gateway for PayPal subscriptions.

Note that this uses the express checkout method through paypal.

Requirements
------------
- Be able to make a payment through PayPal Express checkout.
- Be able to select frequency of Billing.
- Be able to create a billing agreement for users.

Payment Gateway
---------------

This payment gateway forces the user to go through subsciptions in paypal. A billing agreement is create and then a user is billed at the desired interval.

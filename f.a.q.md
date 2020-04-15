# F.A.Q

### I have a payment gateway/shipping method enabled for a role, but when I checkout as that role, the payment/shipping option is not available. ?

Confirm that the shipping method or payment gateway is available to the user when the extension is disabled. A payment gateway or shipping method still won’t appear at checkout if the method or gateway has used its own parameters to determine unavailability.

For example, a shipping method may not be available to customers entering certain billing information, or if products in the cart don’t have dimension or weight information available.

Additionally, the site Admin may have disabled certain shipping sub-methods. The Payment/Shipping Roles extension preserves availability as configured in the specific payment gateway or shipping role settings.


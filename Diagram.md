```mermaid
flowchart TD
    A[Order Placed] --> B{Payment Method?}
    B -->|Credit Card| C[Process Payment]
    B -->|PayPal| D[Redirect to PayPal]
    C --> E[Confirm Order]
    D --> E
    E --> F[Ship Order]
- *A (Order Placed)*: The initial step where a customer places an order.
- *B (Payment Method?)*: A decision point where the system checks the payment method.
- *C (Process Payment)*: The action taken to process the payment if using a credit card.
- *D (Redirect to PayPal)*: The action taken if the customer chooses PayPal as the payment option.
- *E (Confirm Order)*: The step that confirms the order after payment processing.
- *F (Ship Order)*: The final step where the order is shipped to the customer.

Below the diagram, provide a brief description:

```markdown
## Order Processing Flowchart

This flowchart represents the steps involved in processing an online order.

- *Order Placed*: This is the starting point where the customer initiates an order.
- *Payment Method?*: At this decision point, the system determines which payment method the customer has selected.
    - If the customer chooses *Credit Card*, the flow continues to *Process Payment*.
    - If the customer chooses *PayPal*, they are redirected to PayPal for payment.
- *Process Payment*: This step handles the credit card payment processing.
- *Redirect to PayPal*: This step handles the customer’s redirection to PayPal for payment.
- *Confirm Order*: After payment is processed (either through credit card or PayPal), the order is confirmed.
- *Ship Order*: Finally, the order is shipped to the customer.

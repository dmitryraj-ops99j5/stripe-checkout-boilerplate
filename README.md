# stripe-checkout-boilerplate

I got tired of logging into the Stripe dashboard to generate payment links for one-off invoices. This script creates a Checkout session from the command line and copies the URL to my clipboard.

## install

pip install -r requirements.txt

## usage

The session URL is printed to stdout and copied to clipboard if `pyperclip` is available. Amounts are in smallest currency unit (cents/pence).

<!-- verified: 2026-10-06 -->

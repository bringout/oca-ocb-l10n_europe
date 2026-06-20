# Italy - Stock DDT


Documento di Trasporto (DDT)

Whenever goods are transferred between A and B, the DDT serves
as a legitimation e.g. when the police would stop you.

When you want to print an outgoing picking in an Italian company,
it will print you the DDT instead.  It is like the delivery
slip, but it also contains the value of the product,
the transportation reason, the carrier, ... which make it a DDT.

We also use a separate sequence for the DDT as the number should not
have any gaps and should only be applied at the moment the goods are sent.

When invoices are related to their sale order and the sale order with the
delivery, the system will automatically calculate the linked DDTs for every
invoice line to export in the FatturaPA XML.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_it_stock_ddt
```

## Dependencies

- l10n_it_edi
- stock_delivery
- stock_account

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 18.0
- Path: addons/l10n_it_stock_ddt

## License

This package preserves the original LGPL-3 license.

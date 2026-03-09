# Switzerland - Accounting


Swiss localization
==================
This module defines a chart of account for Switzerland (Swiss PME/KMU 2015), taxes and enables the generation of a QR-bill when you print an invoice or send it by mail.
The QR bill is attached to the invoice and eases its payment.

A QR-bill will be generated if:
    - The partner set on your invoice has a complete address (street, city, postal code and country) in Switzerland
    - The option to generate the Swiss QR-code is selected on the invoice (done by default)
    - A correct account number/QR IBAN is set on your bank journal
    - (when using a QR-IBAN): the payment reference of the invoice is a QR-reference

The generation of the QR-bill is automatic if you meet the previous criteria. The QR-bill will be appended after the invoice when printing or sending by mail.

    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_ch
```

## Dependencies

- account
- account_edi_ubl_cii
- base_iban
- l10n_din5008

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 19.0
- Path: addons/l10n_ch

## License

This package preserves the original LGPL-3 license.

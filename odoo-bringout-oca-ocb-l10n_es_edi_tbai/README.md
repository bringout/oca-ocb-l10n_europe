# Spain - TicketBAI


This module sends invoices and vendor bills to the "Diputaciones
Forales" of Araba/Álava, Bizkaia and Gipuzkoa.

Invoices and bills get converted to XML and regularly sent to the
Basque government servers which provides them with a unique identifier.
A hash chain ensures the continuous nature of the invoice/bill
sequences. QR codes are added to emitted (sent/printed) invoices,
bills and tickets to allow anyone to check they have been declared.

You need to configure your certificate and the tax agency.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_es_edi_tbai
```

## Dependencies

- l10n_es_edi_sii

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 17.0
- Path: addons/l10n_es_edi_tbai

## License

This package preserves the original LGPL-3 license.

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

This addon depends on:
- l10n_es_edi_sii

## Manifest Information

- **Name**: Spain - TicketBAI
- **Version**: 1.0
- **Category**: Accounting/Localizations/EDI
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_es_edi_tbai`.

## License

This package maintains the original LGPL-3 license from the upstream Odoo project.

## Documentation

- Overview: doc/OVERVIEW.md
- Architecture: doc/ARCHITECTURE.md
- Models: doc/MODELS.md
- Controllers: doc/CONTROLLERS.md
- Wizards: doc/WIZARDS.md
- Install: doc/INSTALL.md
- Usage: doc/USAGE.md
- Configuration: doc/CONFIGURATION.md
- Dependencies: doc/DEPENDENCIES.md
- Troubleshooting: doc/TROUBLESHOOTING.md
- FAQ: doc/FAQ.md

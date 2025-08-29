# Italy - E-invoicing (PA)


Public Administration partners flow handling for the E-invoice implementation for Italy.

    Several more fields are required for invoicing Public Administration businesses.
    The Origin Document is to be exported in the XML when invoicing the Public Administration,
    It can be a Contract, an Agreement, a Purchase Order, a Linked Invoice or a Down Payment,
    it will need the CIG and CUP fields which are mandatory.
    They both serve the purpose to trace public funds being invested on purchases.
    CIG is the Tender Unique Identifier, CUP identifies the Public Project of Investment.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_it_edi_pa
```

## Dependencies

This addon depends on:
- l10n_it_edi

## Manifest Information

- **Name**: Italy - E-invoicing (PA)
- **Version**: 0.1
- **Category**: Accounting/Localizations/EDI
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_it_edi_pa`.

## License

This package maintains the original LGPL-3 license from the upstream Odoo project.

## Documentation

- Overview: doc/OVERVIEW.md
- Architecture: doc/ARCHITECTURE.md
- Models: doc/MODELS.md
- Controllers: doc/CONTROLLERS.md
- Wizards: doc/WIZARDS.md
- Reports: doc/REPORTS.md
- Security: doc/SECURITY.md
- Install: doc/INSTALL.md
- Usage: doc/USAGE.md
- Configuration: doc/CONFIGURATION.md
- Dependencies: doc/DEPENDENCIES.md
- Troubleshooting: doc/TROUBLESHOOTING.md
- FAQ: doc/FAQ.md

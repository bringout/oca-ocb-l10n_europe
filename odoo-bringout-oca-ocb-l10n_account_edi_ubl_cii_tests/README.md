# Testing the Import/Export invoices with UBL/CII


    This module tests the module 'account_edi_ubl_cii', it is separated since dependencies to some 
    localizations were required. Its name begins with 'l10n' to not overload runbot.
    
    The test files are separated by sources, they were taken from:
    
    * the factur-x doc (form the FNFE)
    * the peppol-bis-invoice-3 doc (the github repository: https://github.com/OpenPEPPOL/peppol-bis-invoice-3/tree/master/rules/examples contains examples)
    * odoo, these files pass all validation tests (using ecosio or the FNFE validator)
    
    We test that the external examples are correctly imported (currency, total amount and total tax match).
    We also test that generating xml from odoo with given parameters gives exactly the same xml as the expected, 
    valid ones.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_account_edi_ubl_cii_tests
```

## Dependencies

This addon depends on:
- l10n_generic_coa
- account_edi_ubl_cii
- l10n_fr
- l10n_be
- l10n_de
- l10n_nl
- l10n_au

## Manifest Information

- **Name**: Testing the Import/Export invoices with UBL/CII
- **Version**: 1.0
- **Category**: Hidden/Tests
- **License**: LGPL-3
- **Installable**: True

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_account_edi_ubl_cii_tests`.

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

# l10n_it_stock_ddt


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

This addon depends on:
- l10n_it_edi
- delivery
- stock_account

## Manifest Information

- **Name**: l10n_it_stock_ddt
- **Version**: 0.1
- **Category**: Accounting/Localizations/EDI
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_it_stock_ddt`.

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

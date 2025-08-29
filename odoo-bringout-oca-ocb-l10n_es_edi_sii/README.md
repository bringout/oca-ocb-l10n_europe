# Spain - SII EDI Suministro de Libros


        This module sends the taxes information (mostly VAT) of the 
        vendor bills and customer invoices to the SII.  It is called 
        Procedimiento G417 - IVA. Llevanza de libros registro.  It is 
        required for every company with a turnover of +6M€ and others can 
        already make use of it.  The invoices are automatically 
        sent after validation.  
        
        How the information is sent to the SII depends on the 
        configuration that is put in the taxes.  The taxes 
        that were in the chart template (l10n_es) are automatically 
        configured to have the right type.  It is possible however 
        that extra taxes need to be created for certain exempt/no sujeta reasons.   
        
        You need to configure your certificate and the tax agency.  
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_es_edi_sii
```

## Dependencies

This addon depends on:
- l10n_es
- account_edi

## Manifest Information

- **Name**: Spain - SII EDI Suministro de Libros
- **Version**: 1.0
- **Category**: Accounting/Localizations/EDI
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_es_edi_sii`.

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

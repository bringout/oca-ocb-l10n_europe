# Luxembourg - Accounting


This is the base module to manage the accounting chart for Luxembourg.
======================================================================

    * the Luxembourg Official Chart of Accounts (law of June 2009 + 2015 chart and Taxes),
    * the Tax Code Chart for Luxembourg
    * the main taxes used in Luxembourg
    * default fiscal position for local, intracom, extracom

Notes:
    * the 2015 chart of taxes is implemented to a large extent,
      see the first sheet of tax.xls for details of coverage
    * to update the chart of tax template, update tax.xls and run tax2csv.py


## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_lu
```

## Dependencies

- account
- base_iban
- base_vat
- account_edi_ubl_cii

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 19.0
- Path: addons/l10n_lu

## License

This package preserves the original LGPL-3 license.

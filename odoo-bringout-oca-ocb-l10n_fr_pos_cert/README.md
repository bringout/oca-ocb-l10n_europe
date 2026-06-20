# France - VAT Anti-Fraud Certification for Point of Sale (CGI 286 I-3 bis)


This add-on brings the technical requirements of the French regulation CGI art. 286, I. 3° bis that stipulates certain criteria concerning the inalterability, security, storage and archiving of data related to sales to private individuals (B2C).
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Install it if you use the Point of Sale app to sell to individuals.

The module adds following features:

    Inalterability: deactivation of all the ways to cancel or modify key data of POS orders, invoices and journal entries

    Security: chaining algorithm to verify the inalterability

    Storage: automatic sales closings with computation of both period and cumulative totals (daily, monthly, annually)

    Access to download the mandatory Certificate of Conformity delivered by Odoo SA (only for Odoo Enterprise users)


## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_fr_pos_cert
```

## Dependencies

- l10n_fr
- point_of_sale

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 17.0
- Path: addons/l10n_fr_pos_cert

## License

This package preserves the original LGPL-3 license.

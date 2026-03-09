# Third Party and Deferred/Electronic Checks Management


Own Checks Management
---------------------

Extends 'Check Printing Base' module to manage own checks with more features:

* allow using own checks that are not printed but filled manually by the user
* allow to use deferred or electronic checks
  * printing is disabled
  * check number is set manually by the user
* add an optional "Check Cash-In Date" for post-dated checks (deferred payments)
* add a menu to track own checks

Third Party Checks Management
-----------------------------

Add new "Third party check Management" feature.

There are 2 main Payment Methods additions:

* New Third Party Checks:

  * Payments of this payment method represent the check you get from a customer when getting paid (from an invoice or a manual payment)

* Existing Third Party check.

  * Payments of this payment method are to track moves of the check, for eg:

    * Use a check to pay a vendor
    * Deposit the check on the bank
    * Get the check back from the bank (rejection)
    * Get the check back from the vendor (a rejection or return)
    * Transfer the check from one third party check journal to the other (one shop to another)

  * Those operations can be done with multiple checks at once


## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_latam_check
```

## Dependencies

- account
- base_vat

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 19.0
- Path: addons/l10n_latam_check

## License

This package preserves the original LGPL-3 license.

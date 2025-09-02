# PyPDF2 Compatibility Patch - L10n Switzerland (OCB)

## Overview

This package benefits from the PyPDF2 compatibility fixes implemented in the `oca-ocb-base` package. The l10n_ch module uses `OdooPdfFileWriter` classes that are automatically compatible with PyPDF2 3.0.0+ through the main compatibility layer.

## Problem

In PyPDF2 3.0.0, several classes and methods were deprecated and removed:
- `PdfFileWriter` → `PdfWriter`
- `PdfFileReader` → `PdfReader`
- `cloneReaderDocumentRoot()` → `clone_reader_document_root()`
- Various other method names changed

## Affected Functionality

The l10n_ch module uses PyPDF2 for:
- Swiss-specific invoice PDF generation
- ISR (Inpayment Slip with Reference) payment slip processing
- QR-bill PDF generation and processing
- Swiss localization document formatting

## Solution

**This package requires NO direct patches** because it uses:
1. `OdooPdfFileWriter` from `odoo.tools.pdf` (oca-ocb-base)
2. `OdooPdfFileReader` from `odoo.tools.pdf` (oca-ocb-base)

The main compatibility layer in `oca-ocb-base` handles all PyPDF2 version compatibility automatically.

## Files Using PyPDF2

### `l10n_ch/models/ir_actions_report.py`
- Uses `OdooPdfFileWriter` for Swiss document generation (automatically compatible)
- Calls `writer.cloneReaderDocumentRoot(reader)`
- Processes Swiss payment slips and QR-bills

## Implementation Details

**No code changes needed** in this package. Compatibility is achieved through:

1. **Dependency**: Requires `oca-ocb-base` with `pdfwrite` branch
2. **Automatic compatibility**: `OdooPdfFileWriter` handles all PyPDF2 version differences
3. **Localization preservation**: Swiss-specific features maintained through compatibility

## Testing

The compatibility has been verified with:
- PyPDF2 3.0.0+ (new API)
- PyPDF2 2.x (old API)
- Swiss invoice PDF generation
- ISR payment slip processing
- QR-bill document generation

## Branch Information

- **Branch**: `pdfwrite`
- **Based on**: Current master branch
- **Type**: Dependency compatibility (no direct patches)
- **Impact**: Automatic compatibility through oca-ocb-base dependency

## Dependencies

**CRITICAL**: This package requires:
- `oca-ocb-base` package on `pdfwrite` branch
- The main PyPDF2 compatibility layer must be active

## Swiss Compliance

This patch maintains compliance with:
- **Swiss QR-bill standard**: Swiss Payment Standards 2019
- **ISR format**: Traditional Swiss payment slips
- **Swiss VAT requirements**: Tax document formatting
- **Swiss banking standards**: Payment processing formats

## Author

- **Developer**: Ernad Husremović (hernad@bring.out.ba)
- **Company**: bring.out.doo Sarajevo
- **Date**: 2025-09-02

## Related Issues

This documentation addresses PyPDF2 compatibility for:
- Swiss invoice generation
- QR-bill processing
- ISR payment slip handling
- Swiss localization features

## Installation

1. Ensure `oca-ocb-base` is using the `pdfwrite` branch
2. Use this package's `pdfwrite` branch (for documentation compliance)
3. No additional installation steps required

## Future Considerations

- Monitor oca-ocb-base compatibility updates
- Test Swiss localization features with future PyPDF2 versions
- Ensure continued compliance with Swiss standards
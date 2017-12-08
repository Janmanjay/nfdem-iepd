# IEPD for the Nuclear Forensics Data Exchange Model (NFDEM)

This IEPD is designed to support nuclear forensics investigation and analysis. It is implemented using NIEM 4.0 and other domain-specific schemas, and created by using the Template-IEPD project  (https://github.com/cdmgtri/Template-IEPD).

The initial release of the NFDEM-IEPD is be compliant with the [NIEM-MPD 3.0.1 specification](https://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html)

## This IEPD contains

1. [NIEM schema subset](http://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_4.2)

    - The [NIEM Schema Subset Generation Tool (SSGT)](http://tools.niem.gov/niemtools/) was used to create a subset for the IEPD based on the several community domain models in NIEM, including CBRN, Emergency, and Biometrics.

2. [NIEM extension schema](http://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_4.3)

    - The extension schema for the NFDEM-IEPD is called nfdem.xsd that is compliant with the NIEM 4.0 specification.

3. [Catalog file](http://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_5.1)

    - The catalog file for this IEPD is the mpd-catalog.xml that follows the catalog schema  [mpd-catalog-3.0.xsd](https://reference.niem.gov/niem/specification/model-package-description/3.0.1/xsd-mpd-catalog/mpd-catalog-3.0.xsd).

4. [README](http://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_5.4)
    - This is defined in README.md (this file).

5. [Change Log](http://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_5.3)
    - A change log is provided in the changelog.txt file.

6. [Conformance Assertion](http://reference.niem.gov/niem/specification/model-package-description/3.0.1/model-package-description-3.0.1.html#section_5.7)

    - Conformance Tests have been performed using the test tool [Conformance Testing Assistant (ConTesA)](https://tools.niem.gov/contesa/) with automated testing targets using the [NDR](https://reference.niem.gov/niem/specification/naming-and-design-rules/) rules on IEPD extension schemas and to generate a conformance assertion.
    - Note that all local NIEM extension schemas must have a conformance target identifier as specified above in order for the NDR rules to be applied.

# R Submissions Pilot 4 ECTD Package

2025-06-13T15:54:51+00:00

> Do not include `README.md` and `.gitignore` files into the final
> submission.

## Overview

The objective of the R Consortium R submission Pilot 4 Project is to
test the concept that a Shiny application created with the R-language
can be bundled with novel technologies and transferred successfully to
FDA reviewers. The application was built as part of the R Consortium
Submission Pilot 2 Project with materials available on the
[RConsortium/submissions-pilot2](https://github.com/RConsortium/submissions-pilot2)
repository, The novel technologies evaluated in Pilot 4 are the
following:

- WebAssembly
- Container Technology

This repository addresses the container technology portion. All
submission materials and communications from this pilot are publicly
available, with the aim of providing a working example for future R
language based FDA submissions. This is a FDA-industry collaboration
through the non-profit organization R consortium.

To learn more about other pilots, visit [the R consortium R submission
working group website](https://rconsortium.github.io/submissions-wg/)
and the [R consortium working group
page](https://www.r-consortium.org/projects/isc-working-groups).

## FDA Response

- Initial submission

## Folder Structure

The folder is organized as a demo eCTD package following ICH guidance.

eCTD package:

- `m1/`: module 1 of the eCTD package

<!-- -->

    m1
    └── us
        ├── cover-letter.pdf  # Submission cover letter

- `m5/`: module 5 of the eCTD package

<!-- -->

    m5
    └── datasets
        └── rconsortiumpilot4container
            └── analysis
                └── adam
                    ├── datasets               # ADaM datasets in XPT format
                    │   ├── adadas.xpt
                    │   ├── adlbc.xpt
                    │   ├── adrg.pdf           # Analysis Data Reviewer's Guide
                    │   ├── adsl.xpt
                    │   ├── adtte.xpt
                    │   ├── define.xml         # ADaM data define file
                    │   └── define2-0-0.xsl
                    └── programs
                        ├── Dockerfile.txt # Docker container build instructions
                        └── r1pkg.txt

Other files: (**Do not include in eCTD package**)

- `.gitignore`: git ignore file
- `README.md`: readme file for github repo

## News

The ECTD bundle and associated compiled application archive were last
rendered on 2025-06-13T15:54:51+00:00 .

## Questions

Report issues in
<https://github.com/RConsortium/submissions-pilot4-container/issues>

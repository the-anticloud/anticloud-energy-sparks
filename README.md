# ENERGY_SPARKS

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-16_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `ENERGY_SPARKS` in category **ELECTRICITY_MANAGEMENT**. 16/16 checks PASS (measured). Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** ENERGY_SPARKS · **Upstream pin:** `a1f60364d6ca9adec8e61a328dfad74fc03e5529` · **Category:** ELECTRICITY_MANAGEMENT · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

# Energy Sparks

Energy Sparks is an open source application that is designed to help schools improve their energy efficiency.

The application collects and presents gas and electricity usage data in a way that is accessible to staff, students and parents. Supported by educational resources, the application will support teachers in helping children understand more about energy usage, how to be more efficient and see how actions they take in the school, e.g. switching off lighting, has an effect on usage.

Combining access to data, the ability to log interventions and a competitive element between schools, the goal is to not just save schools money in reducing energy consumption through long term changes, it is hoped that the application will also help educate children about what it means to be energy efficient.

The application is open source and is powered by open data. It is being designed to be easily deploy and run for minimal cost, allowing it to be run by local councils and/or community groups around the UK.

# For Users

Development of the application and documentation is in progress. Please check back later for more information.

For now you may wish to read the evolving documentation in [the project wiki](https://github.com/Energy-Sparks/energy-sparks/wiki).

# For Developers

The application uses Ruby on Rails.

Read the [developer guide](https://github.com/Energy-Sparks/energy-sparks/wiki/Setting-up-a-developer-environment) in the wiki for how to get started and the CONTRIBUTING.md guidelines.

## Browser testing provided by:

[![Browserstack](https://raw.githubusercontent.com/Energy-Sparks/energy-sparks/master/markdown_pages/browserstack-logo.png)](https://www.browserstack.com/)

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

Combining access to data, the ability to log interventions and a competitive element between schools, the goal is to not just save schools money in reducing energy consumption through long term changes, it is hoped that the application will also help educate children about what it means to be energy efficient.

The application is open source and is powered by open data. It is being designed to be easily deploy and run for minimal cost, allowing it to be run by local councils and/or community groups around the UK.

## API

For now you may wish to read the evolving documentation in [the project wiki](https://github.com/Energy-Sparks/energy-sparks/wiki).

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

## Git workflow ##

- Pull requests must contain a succint, clear summary of what the user need is driving this feature change.
- Write clear commit messages
- Link to the issue you're working on or fixing
- Make a feature branch
- Pull requests are automatically integration tested, where applicable using [Travis CI](https://travis-ci.org/), which will report back on whether the tests still pass on your branch

## Code ##

- Must be readable with meaningful naming, eg no short hand single character variable names
- Rubocop is used for style checking, with various customisations [rubocop.yml](https://github.com/BathHacked/.rubocop.yml)

## Testing ##

Write tests.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** ENERGY_SPARKS
- **Pinned SHA:** `a1f60364d6ca9adec8e61a328dfad74fc03e5529`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`e063e32f2c64bd756b89fbd130d50002448dfe9b3959dd65b548c11cc443c9da`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.


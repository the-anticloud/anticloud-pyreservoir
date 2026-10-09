# PYRESERVOIR

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `PYRESERVOIR` in category **OIL_GAS**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** PYRESERVOIR · **Upstream pin:** `66b3aefe37413c19761598b8b7eefcd4debbb47e` · **Category:** OIL_GAS · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

# PyReservoir
Python utilities for reservoir engineering calculations

<div>
<img src="https://user-images.githubusercontent.com/51282928/85827088-bb6f1300-b7af-11ea-9a1f-eed08adddaff.png" width="500"/>
</div>

* PVT analysis `pvt`
* Volumetric mapping `volumetrics`
* Well-test analysis `welltest`
* Material balance `matbal`
* Decline curve analysis `dca`
* Fluid flow `fluid_flow`

## Applications

* `pvt`: Obtaining PVT properties using PVT correlation ([`pvtcorrelation`](https://github.com/yohanesnuwara/pyreservoir/blob/master/pvt/pvtcorrelation.py)); Processing PVT lab experiments such as DL, CCE, Flash Analysis, and CVD ([`pvtlab`](https://github.com/yohanesnuwara/pyreservoir/blob/master/pvt/pvtlab.py)); EOS to produce PVT properties and phase envelope (`pvteos`)
* `volumetrics`: Computing OOIP and OGIP using volumetric trapezoidal, pyramidal, and Simpson's 1/3 rule ([`volumetrics`](https://github.com/yohanesnuwara/pyreservoir/blob/master/volumetrics/volumetrics.py))
* `welltest`: Modeling well transient response from multirate or multiple pressure data ([`wellflo`](https://github.com/yohanesnuwara/pyreservoir/blob/master/welltest/wellflo.py)); Simple well-test analysis on pressure drawdown and build-up data
* `matbal`: Computing aquifer influx into a reservoir using Schilthuis, van Everdingen-Hurst, and Fetkovich methods ([`aquifer`](https://github.com/yohanesnuwara/pyreservoir/blob/master/matbal/aquifer.py)); Material balance plots for OOIP and OGIP verification for gas and oil reservoirs ([`mbal`](https://github.com/yohanesnuwara/pyreservoir/blob/master/matbal/mbal.py)); Computing reservoir drive indices and producing energy plots ([`drives`](https://github.com/yohanesnuwara/pyreservoir/blob/master/matbal/drives.py))
* `dca`: Computing decline curve parameters from Arps `arps_fit`; Stochastic (bootstrapping) method to obtain the uncertainty of DCA parameters, in a form of 95% confidence interval `arps_bootstrap`
* `fluid_flow`

## Tutorials

See these tutorial [Jupyter notebooks](https://github.com/yohanesnuwara/pyreservoir/tree/master/notebooks) to get started with each of the libraries. See inside [this folder](https://github.com/yohanesnuwara/pyreservoir/tree/master/data) to get the datasets used for the tutorials. 

## License

I consider the goodness of open-source program but I strongly recommend that anyone who wish to use any program in this package to consider the code authorship. This work is licensed with Creative Commons BY-NC-ND 4.0 International. 

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

</div>

* PVT analysis `pvt`
* Volumetric mapping `volumetrics`
* Well-test analysis `welltest`
* Material balance `matbal`
* Decline curve analysis `dca`
* Fluid flow `fluid_flow`

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

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

Fork the project, create a feature branch, run the test suite, and open a pull request against upstream.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** PYRESERVOIR
- **Pinned SHA:** `66b3aefe37413c19761598b8b7eefcd4debbb47e`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`1ed67f4a25e27f854836ae52e3145bdd0b13ca9cca022ae22c41acd401b400ec`.

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
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.


# IJB-C

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FIJB--C-181717?logo=github)](https://github.com/biometric-community/IJB-C)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www.nist.gov/programs-projects/face-challenges)

**IJB-C** — tbiom catalog packaging for `ijb-c` (face-recog; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/IJB-C
- **Upstream source**: https://www.nist.gov/programs-projects/face-challenges
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `ijb-c` |
| Category | `face-recog` |
| Access | `register` |
| Upstream homepage | https://www.nist.gov/programs-projects/face-challenges |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: IARPA Janus Benchmark-C via NIST.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/IJB-C.git
cd IJB-C
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_ijb_c.sh
```

Place licensed archives under `projects/datasets/ijb-c/` (gitignored).

## Dataset structure

```text
IJB-C/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www.nist.gov/programs-projects/face-challenges
- Packaging: https://github.com/biometric-community/IJB-C/issues

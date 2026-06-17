# nf-core/demo: Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.2.0dev - [date]

### Credits

Special thanks to the following for their reviews and assistance:

- [Jen Reeve](https://github.com/jen-reeve)

### Changed

- [#54] Changed the `test_full.config` input samplesheet

## [1.1.0](https://github.com/nf-core/demo/releases/tag/1.1.0) - 2026-01-26

### Credits

Special thanks to the following for their reviews and assistance:

- [Phil Ewels](https://github.com/ewels)
- [Matthias Hörtenhuber](https://github.com/mashehu)
- [Maxime Garcia](https://github.com/maxulysse)

### Changed

- [#49](https://github.com/nf-core/demo/pull/49) - Template update for nf-core/tools v3.4.1 and v3.5.1
- Updated nf-core modules and subworkflows
- Bump nf-schema and minimum Nextflow version
- Use topic channels for version handling
- Update pipeline to meet requirements for Nextflow's "strict syntax"
- Add mimetype to schema for `params.input`

### Fixed

- Fix all warnings from `nextflow lint`

### Dependencies

| Dependency | Old version | New version |
| ---------- | ----------- | ----------- |
| `multiqc`  | 1.25.1      | 1.33        |
| `nextflow` | 24.04.2     | 25.10.2     |

## 1.0.2

### Credits

Special thanks to the following for their reviews and assistance:

- [Chris Hakkaart](https://github.com/christopher-hakkaart)
- [Marcel Ribeiro-Dantas](https://github.com/mribeirodantas)
- [Maxime Garcia](https://github.com/maxulysse)
- [Geraldine Van der Auwera](https://github.com/vdauwera)
- [Florian Wuennemann](https://github.com/FloWuenne)

### Changed

[#39][https://github.com/nf-core/demo/pull/39] - Remove -C from bach in nextflow.config
[#38][https://github.com/nf-core/demo/pull/38] - Template update for nf-core/tools v3.3.1
[#36][https://github.com/nf-core/demo/pull/36] - Template update for nf-core/tools v3.2.1
[#34][https://github.com/nf-core/demo/pull/34] - updated nextflow_schema.json
[#32][https://github.com/nf-core/demo/pull/32] - Minor fixes and template update
[#29](https://github.com/nf-core/demo/pull/29) - Template update for nf-core/tools v3.2.0
[#23](https://github.com/nf-core/demo/pull/23) - Update to latest `seqtk` and `fastqc` modules
[#21](https://github.com/nf-core/demo/pull/21) - Template update for nf-core/tools v3.1.0
[#21](https://github.com/nf-core/demo/pull/21) - Fix memory and usage limits

## [1.0.1](https://github.com/nf-core/demo/releases/tag/1.0.1) 2024-10-18

### Credits

Special thanks to the following for their reviews and assistance:

- [Matthias Hörtenhuber](https://github.com/mashehu)
- [Chris Hakkaart](https://github.com/christopher-hakkaart)
- [Maxime Garcia](https://github.com/maxulysse)
- [Friederike Hanssen](https://github.com/FriederikeHanssen)

### Changed

[#14](https://github.com/nf-core/demo/pull/14) - Update to template 3.0.2
[#7](https://github.com/nf-core/demo/pull/7) - Updated Usage and README docs

### Fixed

[#15](https://github.com/nf-core/demo/pull/15) - Add background to subway map
[#7](https://github.com/nf-core/demo/pull/7) - Fixed full path for `test.config`

### Dependencies

| Dependency | Old version | New version |
| ---------- | ----------- | ----------- |
| `multiqc`  | 1.21        | 1.25.1      |

## [1.0.0](https://github.com/nf-core/demo/releases/tag/1.0.0) 2024-06-19

### Credits

Special thanks to the following for their reviews and assistance:

- [Maxime Garcia](https://github.com/maxulysse)
- [Friederike Hanssen](https://github.com/FriederikeHanssen)

### Added

- `nf-core/seqtk/trim` module
- `skip_trim` parameter

## v1.0dev - 2024-05-5

Initial release of nf-core/demo, created with the [nf-core](https://nf-co.re/) template.

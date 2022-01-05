# Trait-based Approaches to Modeling Trophic Interactions Under Global Change 

## Manuscript description

I think that you should write your thesis in a reproducible and open way, so I've decided to write all of the thesis content itself here on GitHub where it can in theory be accessible to others. Maybe someone will find it useful! Obviously theses themselves are outdated and kind of weird concepts seeing as the actual unit of measure is a published paper...but apparently I have to do this anyways so here it will be. 

### Repository directories & files

I have two main repos that contain the actual work that this thesis works off of. 

The directories and main files are as follows:
+ [`trait-based-rewiring`](https://github.com/colebrookson/trait-based-rewiring) this repo contains the work for my chapter on trait-based rewiring of whole food webs. Therein is all the work for the actual project itself which has it's own associated manuscript. 
+ [`tuna-diet-prediction`](https://github.com/colebrookson/tuna-diet-prediction) this repo contains the work for my chapter on predicting how tuna diets can be predicted using a varietyf of methods. Therein is all the work for the actual project itself which has it's own associated manuscript. 
+ [`content`](content) contains the manuscript source, which includes markdown files as well as inputs for citations and references.
+ [`output`](output) (and the `output` and `gh-pages` branches) contains the outputs (generated files) from Manubot including the resulting manuscript files (in `HTML`, `PDF`, and other formats).

+ [`webpage`](webpage) is a directory meant to be rendered as a static webpage for viewing the HTML manuscript.
+ [`build`](build) contains commands and tools for building the manuscript.
+ [`ci`](ci) contains files necessary for deployment via continuous integration.
+ [LICENSE.md](LICENSE.md) and [LICENSE-CC0.md](LICENSE-CC0.md) contain the licenses associated with Manubot and with the content we are developing in this project. Please see the "License" section below.

### Continuous Integration

Whenever a pull request is opened, CI (continuous integration) will test whether the changes break the build process to generate a formatted manuscript.
The build process aims to detect common errors, such as invalid citations. 

For continuous integration configuration details, see [`.github/workflows/manubot.yaml`](.github/workflows/manubot.yaml).

## License

<!--
usage note: edit this section to change the license of your manuscript or source code changes to this repository.
We encourage users to openly license their manuscripts, which is the default as specified below.
-->

[![License: CC BY 4.0](https://img.shields.io/badge/License%20All-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
[![License: CC0 1.0](https://img.shields.io/badge/License%20Parts-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Except when noted otherwise, the entirety of this repository is licensed under a CC BY 4.0 License ([`LICENSE.md`](LICENSE.md)), which allows reuse with attribution.
Please attribute by linking to https://github.com/SORTEE-Github-Hackathon/manuscript.

Since CC BY is not ideal for code and data, certain repository components are also released under the CC0 1.0 public domain dedication ([`LICENSE-CC0.md`](LICENSE-CC0.md)).
All files matched by the following glob patterns are dual licensed under CC BY 4.0 and CC0 1.0:

+ `*.sh`
+ `*.py`
+ `*.yml` / `*.yaml`
+ `*.json`
+ `*.bib`
+ `*.tsv`
+ `.gitignore`

All other files are only available under CC BY 4.0, including:

+ `*.md`
+ `*.html`
+ `*.pdf`
+ `*.docx`

## About Manubot

<!-- usage note: do not edit this section -->

Manubot is a system for writing scholarly manuscripts via GitHub.
Manubot automates citations and references, versions manuscripts using git, and enables collaborative writing via GitHub.
An [overview manuscript](https://greenelab.github.io/meta-review/ "Open collaborative writing with Manubot") presents the benefits of collaborative writing with Manubot and its unique features.
The [rootstock repository](https://git.io/fhQH1) is a general purpose template for creating new Manubot instances, as detailed in [`SETUP.md`](SETUP.md).
See [`USAGE.md`](USAGE.md) for documentation how to write a manuscript.

Please open [an issue](https://git.io/fhQHM) for questions related to Manubot usage, bug reports, or general inquiries.

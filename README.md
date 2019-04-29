Terraform Metadata
========

This repository contains some metadata for [Terraform](https://www.terraform.io):
 * Providers
 * Providsioners
 * Resources
 * Data Sources
 * Functions

Mostly data is autogenerated using 'schemas-extractor'



### Usage

This metadata is used for [IntelliJ-Terraform plugin](https://plugins.jetbrains.com/plugin/7808).

Plugin may read it from `$HOME/.terraform.d/metadata-repo` (Linux, macOS) or `%APPDATA%/.terraform/metadata-repo` (Windows).
Just clone this repositry there:
```bash
mkdir -p "$HOME/.terraform.d/metadata-repo"
git clone "https://github.com/VladRassokhin/terraform-metadata" "$HOME/.terraform.d/metadata-repo"
```
And then update it regularly using `git pull`

### Update
Follow instructions at schemas-extractor/ReadMe.md


### License

Apache 2.0 for everything here.

Terraform and most of providers source codes are licensed under MPL 2.0.
Since scripts in this repository are using them in terms of 'runtime' Apache 2.0 could be used for the results as well as scripts themselves.

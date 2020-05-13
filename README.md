# {{ repository-name }}

![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/pre-cursor/github-template-repository-terraform)

Terraform module which creates...

These types of resources are supported:

- terraform output

## Terraform versions

Terraform 0.12. Pin module version to `~> v2.0`. Submit pull-requests to `master` branch.

## Usage

**IMPORTANT:** The `master` branch is used in `source` just as an example. In your code, do not pin to `master` because there may be breaking changes between releases.
Instead pin to the release tag (e.g. `?ref=tags/x.y.z`) of one of our [latest releases](https://github.com/pre-cursor/github-template-repository-terraform/releases).

```hcl
module "terraform-sample" {
  source                   = "git::https://github.com/pre-cursor/github-template-repository-terraform.git?ref=master"
  name                     = "thing1"
}
```

## Makefile Targets

```
Available targets:

 help        | Displays the GNU makefile help
 precommit   | Lint the project files using pre-commit
 changelog   | Build the changelog
 release     | Release the product, setting the tag and pushing.
```

  [project_url]: https://github.com/

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| terraform | ~> 0.12.0 |

## Providers

No provider.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| name | resource name | `string` | `"thing"` | no |

## Outputs

| Name | Description |
|------|-------------|
| message | message output |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

## Contributing

### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/pre-cursor/github-template-repository-terraform/issues) to report any bugs or file feature requests.

### Developing

If you are interested in being a contributor and want to get involved in developing this project or [help out](https://github.com/orgs/pre-cursor/projects/1) with our other projects, we would love to hear from you! Shoot us an [email][email].

In general, PRs are welcome. We follow the typical "fork-and-pull" Git workflow.

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Push** your work back up to your fork
 5. Submit a **Pull Request** so that we can review your changes

**NOTE:** Be sure to merge the latest changes from "upstream" before making a pull request!

## Copyright

Copyright (c) 2020 [pre-cursor](https://continuul.solutions/)

## License

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

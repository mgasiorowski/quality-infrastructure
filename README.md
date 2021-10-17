# Quality in infrastructure

Pull requests welcome.

## Table of Contents

=================

* [Legend](#legend)
* [Infrastructure as Code](#infrastructure-as-code)
  * [Static analysis](#static-analysis)
    * [Universal](#universal)
    * [Terraform](#terraform)
    * [AWS Cloudformation](#aws-cloudformation)
    * [Kubernetes](#kubernetes)
    * [Docker](#docker)
    * [Shell scripts](#shell-scripts)
* [Web Links](#web-links)
  * [Testing](#testing)

## Legend

:moneybag: - Paid services, tools, etc.

## Infrastructure as Code

### Static analysis

#### Universal

* [Terrascan](https://github.com/accurics/terrascan)
* [Checkov](https://github.com/bridgecrewio/checkov)
* [KICS](https://kics.io/)
* [config-lint](https://github.com/stelligent/config-lint)
* [Semgrep](https://github.com/returntocorp/semgrep)
* [Trivy](https://github.com/aquasecurity/trivy)
* [Regula](https://github.com/fugue/regula)

#### Terraform

* [TFLint](https://github.com/terraform-linters/tflint)
* [tfsec](https://github.com/aquasecurity/tfsec)
* [HashiCorp Sentinel](https://www.hashicorp.com/sentinel) :moneybag:

#### AWS Cloudformation

* [AWS CloudFormation Linter](https://github.com/aws-cloudformation/cfn-lint)
* [cfn-nag](https://github.com/stelligent/cfn_nag)

#### Kubernetes

* [KubeLinter](https://github.com/stackrox/kube-linter)

#### Docker

* [Haskell Dockerfile Linter](https://github.com/hadolint/hadolint)

#### Shell scripts

* [ShellCheck](https://github.com/koalaman/shellcheck)

## Web Links

### Testing

* [List of resources on testing distributed systems](https://github.com/asatarin/testing-distributed-systems)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

```text
MIT License

Copyright (c) 2021 Maciej Gąsiorowski

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

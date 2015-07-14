## Certificate Service

A work-in-progress system built by 18F to manage the deployment of HTTPS certificates to its production properties.

### Vision

Enabling and maintaining HTTPS for a domain should be a trivial operation for our engineering and operations team.

* Turning on HTTPS for a domain should be a one-button operation.

* Renewing HTTPS for a domain should be a one-button or zero-button (automated) operation.

* A Hearbleed-like situation that requires mass revocation and reissuance should be equally simple and panic-free.


### Engineering ideals

Even if these are not initially captured, some ideals to strive for:

* Any team member should be able to safely attempt to turn on HTTPS for a domain. If our team is not actually in control of that domain, the process should safely fail without charging us any money.

* We should be able to issue certificates using a CA-agnostic interface that wraps specific CA/reseller interactions.

* We should be able to deploy certificates using a host-agnostic interface that wraps specific deployment commands.

### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.


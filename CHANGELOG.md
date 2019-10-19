# Change Log
All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/).

## [2.5.0] - 2019-10-19
### Merged
- Pull #72: Don't swallow the error code
- Pull #74: Create README.md in use-cases
- Pull #82: Update contribution guides of the workflow
- Pull #80: add first timers guide for newcomers
- Pull #65: Added "Code Review" section to CONTRIBUTING.md
- Pull #83: Follow godoc deprecation standards
- Pull #88: Add our Developer Experience Engineer career opportunity to the READM…
- Pull #93: Add current Go versions to Travis
- Special thanks for these PRs to:
    - [Succo](//github.com/Succo)
    - [ajloria](//github.com/ajloria)
    - [radlinskii](//github.com/radlinskii)
    - [daniloff200](//github.com/daniloff200)
    - [aleien](//github.com/aleien)
    - [vaskoz](//github.com/vaskoz)
    - [mptap](//github.com/mptap)
    - [gliptak](//github.com/gliptak)

## [2.4.1] - 2018-4-09
### Fixed
- Pull #71, Solves #70
- Fix Travis CI Build
- Special thanks to [Vasko Zdravevski](https://github.com/vaskoz) for the PR!

## [2.4.0] - 2017-4-10
### Added
- Pull #18, Solves #17
- Add RestError Struct for an error handling
- Special thanks to [Takahiro Ikeuchi](https://github.com/iktakahiro) for the PR!

## [2.3.1] - 2016-10-14
### Changed
- Pull #15, solves Issue #7
- Moved QueryParams processing into BuildRequestObject
- Special thanks to [Gábor Lipták](https://github.com/gliptak) for the PR!

## [2.3.0] - 2016-10-04
### Added
- Pull [#10] [Allow for custom Content-Types](https://github.com/sendgrid/rest/issues/10)

## [2.2.0] - 2016-07-28
### Added
- Pull [#9](https://github.com/sendgrid/rest/pull/9): Allow for setting a custom HTTP client
- [Here](https://github.com/sendgrid/rest/blob/master/rest_test.go#L127) is an example of usage
- This enables usage of the [sendgrid-go library](https://github.com/sendgrid/sendgrid-go) on [Google App Engine (GAE)](https://cloud.google.com/appengine/)
- Special thanks to [Chris Broadfoot](https://github.com/broady) and [Sridhar Venkatakrishnan](https://github.com/sridharv) for providing code and feedback!

## [2.1.0] - 2016-06-10
### Added
- Automatically add Content-Type: application/json when there is a request body

## [2.0.0] - 2016-06-03
### Changed
- Made the Request and Response variables non-redundant. e.g. request.RequestBody becomes request.Body

## [1.0.2] - 2016-04-07
### Added
- these changes are thanks to [deckarep](https://github.com/deckarep). Thanks!
- more updates to error naming convention
- more error handing on HTTP request

## [1.0.1] - 2016-04-07
### Added
- these changes are thanks to [deckarep](https://github.com/deckarep). Thanks!
- update error naming convention
- explicitly define supported HTTP verbs
- better error handing on HTTP request

## [1.0.0] - 2016-04-05
### Added
- We are live!

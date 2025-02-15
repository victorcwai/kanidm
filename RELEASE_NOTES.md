
<p align="center">
  <img src="https://raw.githubusercontent.com/kanidm/kanidm/master/artwork/logo-small.png" width="20%" height="auto" />
</p>

# Getting Started

To get started, see the [kanidm book]

# Feedback

We value your feedback! First, please see our [code of conduct]. If you
have questions please join our [gitter community channel] so that we
can help. If you find a bug or issue, we'd love you to report it to our
[issue tracker].

# Release Notes

## 2021-04-01 - Kanidm 1.1.0-alpha4

This is the fourth alpha series release of the Kanidm Identity Management
project. Alpha releases are to help get feedback and ideas from the community
on how we can continue to make this project better for a future supported release.

### Release Highlights

* Performance Improvements
* TOTP CLI enrollment
* Jemalloc in main server instead of system allocator
* Command line completion
* TLS file handling improvements
* Webauthn authentication and enrollment on CLI
* Add db vacuum task
* Unix tasks daemon that automatically creates home directories
* Support for sk-ecdsa public ssh keys
* Badlist checked at login to determine account compromise
* Minor Fixes for attribute display

## 2021-01-01 - Kanidm 1.1.0-alpha3

This is the third alpha series release of the Kanidm Identity Management
project. Alpha releases are to help get feedback and ideas from the community
on how we can continue to make this project better for a future supported release.

### Release Highlights

* Account "valid from" and "expiry" times.
* Rate limiting and softlocking of account credentials to prevent bruteforcing.
* Foundations of webauthn and multiple credential support.
* Rewrite of json authentication protocol components.
* Unixd will cache "non-existant" items to improve nss/pam latency.

## 2020-10-01 - Kanidm 1.1.0-alpha2

This is the second alpha series release of the Kanidm Identity Management
project. Alpha releases are to help get feedback and ideas from the community
on how we can continue to make this project better for a future supported release.

### Release Highlights

* SIMD key lookups in container builds for datastructures
* Server and Client hardening warnings for running users and file permissions
* Search limits and denial of unindexed searches to prevent denial-of-service
* Dynamic Rounds for PBKDF2 based on CPU performance
* Radius module upgraded to python 3
* On-login PW upgrade, allowing weaker hashes to be re-computed to stronger variants on login.
* Replace actix with tide and async
* Reduction in memory footprint during searches
* Change authentication from cookies to auth-bearer tokens

## 2020-07-01 - Kanidm 1.1.0-alpha1

This is the first alpha series release of the Kanidm Identity Management
project. Alpha releases are to help get feedback and ideas from the community
on how we can continue to make this project better for a future supported release.

It would not be possible to create a project like this, without the contributions
and help of many people. I would especially like to thank:

* Pando85
* Alberto Planas (aplanas)
* Jake (slipperyBishop)
* Charelle (Charcol)
* Leigh (excitedleigh)
* Jamie (JJJollyjim)
* Triss Healy (NiryaAestus)
* Samuel Cabrero (scabrero)
* Jim McDonough

### Release Highlights

* A working identity management server, including database
* RADIUS authentication and docker images
* Pam and Nsswitch resolvers for Linux/Unix authentication
* SSH public key distribution
* LDAP server front end for legacy applications
* Password badlisting and quality checking
* Memberof and reverse group management with referential integrity
* Recycle Bin
* Performance analysis tools

[issue tracker]: https://github.com/kanidm/kanidm/issues
[gitter community channel]: https://gitter.im/kanidm/community
[code of conduct]: https://github.com/kanidm/kanidm/blob/master/CODE_OF_CONDUCT.md
[kanidm book]: https://github.com/kanidm/kanidm/blob/master/kanidm_book/src/SUMMARY.md



# Changelog

## 9 November 2026

* Provenance Records: align the signing and encoding description with the reference implementation:
    * The signature data includes the version, signing certificate serial number and signing timestamp.
    * The signature data includes the signature elements of included Signed Step Lists.
    * Signatures are DER encoded ECDSA using P-256 and SHA-256.
    * Steps, signatures and IDs use base64url encoding.
* Provenance Records: clarifications and example fixes:
    * Schemes MUST NOT add top level properties (previously "MAY NOT").
    * Clarify the format of issuer entries in `certificates`. Verifiers must not trust a root CA certificate included in a record.
    * The receipt checklist checks the Transfer step's `permissions`. It previously named `account`, which is a Permission step property.
    * Add the missing `scheme` to the Permission example and remove a trailing comma.
    * Give the Process example its own `id`. It previously reused the Origin example's `id` and listed itself as an input.

## 26 March 2026

* Fix numbering for dataset assurance level 4.3.1.x

## 26 February 2026

* Add Trust Framework Roles page
* Add badge assets to assurance levels

## 12 February 2025

* Move specifications from docs.icebreakerone.org

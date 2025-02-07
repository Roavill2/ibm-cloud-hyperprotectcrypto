
# Deprecation Notice
Updated GREP11 code example repositories for Go and Javascript have been separated out and moved to the following repositories:
- [Go code example repository](https://github.com/IBM-Cloud/hpcs-grep11-go)
- [Javascript code example repository](https://github.com/IBM-Cloud/hpcs-grep11-js)

In addition, the following repository can be referenced to create additional language specific GREP11 clients:
- [GREP11 API repository](https://github.com/IBM-Cloud/hpcs-grep11)

Please reference the new repositories for all GREP11 API code examples. There will be no future updates to this repository.
# Overview

This repository contains software to be used to connect to the **IBM Cloud Hyper Protect Crypto Services (HPCS)**  offering. For more information regarding this service please review the [HPCS documentation](https://cloud.ibm.com/docs/services/hs-crypto?topic=hs-crypto-get-started).

# Contents

The contents of this repository are offered *as-is* and is subject to change at anytime.

For general information about "Enterprise PKCS #11 over gRPC" please see the official [documentation](https://cloud.ibm.com/docs/services/hs-crypto?topic=hs-crypto-enterprise_PKCS11_overview#grep11_intro)

# Code Examples

The Golang examples can be found [here](golang/README.md), while JavaScript examples can be found in the **js** folder. The examples show how to use the **HPCS offering** to accomplish the following functions:

* Key generation
* Encrypt and decrypt
* Sign and verify
* Wrap and unwrap keys
* Derive keys
* Build message digest
* Retrieve mechanism information

Examples for hyperledger-fabric (e.g. IBM Blockchain Platform) can be found in **js/fabric** folder


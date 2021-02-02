The Industry working on a convergence of industry terms between several glossary efforts, namely:

* ToIP Glossary - UNDER CONSTRUCTION and currently refers to Sovrin Glossary, per ToIP Concepts and Terminology Working Group
* DIF Glossary Working Group](https://dif.groups.io/g/glossary)
* [Sovrin Glossary](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8)
* [NIST Glossary: A Taxonomic Approach to Understanding Emerging Blockchain Identity Management Systems (final)](https://csrc.nist.gov/publications/detail/white-paper/2020/01/14/a-taxonomic-approach-to-understanding-emerging-blockchain-idms/final)

The contents herein are considered additional terms specific to the **Bedrock Business Utility**.

>Note: See [BBU Issue 12](https://github.com/bedrock-consortium/bbu-gf/issues/12)

### Steward
A general term for an organization that is responsible for providing and maintaining a portion of the infrastructure necessary to establish a public identity utility. Minimally, the organization must meet the requirements to be a member of the public identity utility and must operate at least one ```Node```.

### Node
A computer network server running an instance of the code necessary to operate a distributed ledger or blockchain. In the Bedrock Consortium, a Node is operated by a Steward running an instance of the Bedrock Open Source Code to maintain the Bedrock Business Utility ( or DID Ledger). A Node must be either a Validator Node or an Observer Node.

### Bedrock Open Source Code
The computer software that is installed on all Nodes associated with the Bedrock Business Utility (BBU). This code determined by the Bedrock Board of Directors. The BBU adheres to code selection and version guidance provided by the Technical Steering Committee ("TSC") of the Bedrock Technical Project. The TSC collaborates within the Hyperledger Indy Project of the Linux Foundation to establish a TSC approved version of Hyperledger Indy within the the Bedrock Code Repository managed by the TSC.

### Bedrock Ledger Environments
The corpus of DID Ledgers used by the Bedrock Consortium to operate the Bedrock Business Utility. For example: ```prod```, ```test```, and ```dev```.

### DID Namespace

Building on URI Standards, the DID Specification allows for both  root namespace (did:xxx) and sub-namespace (did:xxx:yyy) conventions.

### Governing Body

An organization or consortium that is responsible for the management of a Public Identity Utility.

### Backbone Network

A distinct system of domain specific ledgers operated by decentralized peer nodes and associated with a DID Namespace. Governed by its own governance framework. See also *Public Identity Utility*.

### Peer-Net
> *Deprecated*

A distinct system of domain specific ledgers operated by decentralized peer nodes and associated with a DID Namespace. Governed by its own governance framework. See also *Backbone Network*.

### Network of Networks

A decentralized collection of discoverable and interoperable public identity utilities. The internet is an exemplar of a network of networks structure based on DNS and URI standards.

### DID Ledger

A distinct system of domain specific ledgers operated by decentralized peer nodes and associated with a DID Namespace.
See *Public Identity Utility*

### Public Identity Utility

A distinct system of domain specific ledgers operated by decentralized peer nodes and associated with a DID Namespace. The ```DID Ledger```, is governed by an independent governing body and its own governance framework. Due to the overuse of terms such as "Network" and "Ledger", the term "Utility" has been accepted by the Bedrock Consortium to allow for additional clarity. See also *Backbone Network*.

### Decentralized DID Namespace Registry (DDNR)

Provides registration, discovery, and access for a Public Identity Utility.

### Identity Utility Administrator

See *Utility Service Provider*

### Utility Service Provider

The provider of operational and maintenance services for a Public Identity Utility.

### Trustee
An Identity Owner entrusted with specific identity control responsibilities by another Identity Owner or with specific governance responsibilities by a Governance Framework. See *Recovery Key Trustee*

### Consortium Trustee
A Trustee who is a member of the Bedrock Consortium Board of Directors. The trust in Consortium Trustees is bestowed collectively on behalf of all Identity Owners.

### Key Recovery
The process of recovering access to and control of a set of Private Keys—or an entire Wallet—after loss or compromise. Key Recovery is a major focus of the emerging DKMS standard for cryptographic key management. See also Recovery Key.

### Recovery Key
A special Private Key used for purposes of recovering a Wallet after loss or compromise. In the DKMS key management protocol, a Recovery Key may be cryptographically sharded for secret sharing among multiple Trustees.

### Recovery Key Trustee
A Trustee trusted by another Identity Owner to authorize sharing back a Recovery Key for purposes of restoring a Wallet after loss or compromise.

### Membership Management System
The means by which the Governing Board tracks membership entitlements and status. This MAY be implemented via a Salesforce tenant operated by the Linux Foundation with custom hooks into the Bedrock Business Utility.

### Digital Trust Ecosystem
An interdependent group of enterprises, people and/or things that share a standardized trust model for mutually beneficial purposes, such as consumer and commercial interactions that are verifiable.

### CLI Private Key
The Private-Key used by a Steward when interacting with the Indy CLI.

### Validator Private Key
The Private-Key used by the Validator Node when performing consensus.



# Attestation

### NIST 

> The process of providing a digital signature for a set of measurements securely stored in hardware, 
> and then having the requester validate the signature and the set of measurements.

- [NIST.SP.1800-19](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.1800-19.pdf)
- [csrc.nist.gov/glossary/term/attestation](https://csrc.nist.gov/glossary/term/attestation)

### TCG

> The process of vouching for the accuracy of information. External entities
> can attest to shielded locations, protected capabilities, and Roots of Trust. A
> platform can attest to its description of platform characteristics that affect the
> integrity (trustworthiness) of a platform. Both forms of attestation require reliable evidence of the attesting entity.

- [TCG-Glossary-V1.1-Rev-1.0](https://trustedcomputinggroup.org/wp-content/uploads/TCG-Glossary-V1.1-Rev-1.0.pdf)
- [DICE Attestation Architecture](https://trustedcomputinggroup.org/wp-content/uploads/DICE-Attestation-Architecture-r23-final.pdf)


### IETF

> Attestation Result:
> The output generated by a Verifier, typically including information about an Attester, where the Verifier vouches for the validity of the results.

- [draft-ietf-rats-architecture](https://www.ietf.org/archive/id/draft-ietf-rats-architecture-22.html)


### FIDO

> The terms “assertion” and “attestation” are frequently confused – assertion occurs when authenticating; attestation occurs during registration.

> The attestation is specific to a device model and can be used to cryptographically prove that a user has a specific model of device when they register. 

> Generally speaking, attestation keys have associated attestation certificates, and those certificates chain to a root certificate that the service trusts.  
> This is how the service establishes its trust in the authenticator’s attestation key.

- [fido-technotes-the-truth-about-attestation](https://fidoalliance.org/fido-technotes-the-truth-about-attestation/)


### W3C

> Attestation
> Generally, attestation is a statement serving to bear witness, confirm, or authenticate. 
> In the WebAuthn context, attestation is employed to attest to the provenance of an 
> authenticator and the data it emits; including, for example: credential IDs, 
> credential key pairs, signature counters, etc. 
> An attestation statement is conveyed in an attestation object during registration.  


> Attestation Certificate
> A X.509 Certificate for the attestation key pair used by an authenticator to attest to its manufacture and capabilities. 
> At registration time, the authenticator uses the attestation private key to sign the Relying Party-specific credential public key 
> (and additional data) that it generates and returns via the authenticatorMakeCredential operation.

- [webauthn-2/#attestation](https://www.w3.org/TR/webauthn-2/#attestation)

### EBSIDOC

> This document defines the data model of Verifiable Attestation, a W3C compliant Verifiable Credential.

- [EBSIDOC](https://ec.europa.eu/digital-building-blocks/wikis/display/EBSIDOC/Verifiable+Attestation)

### wiktionary

> A thing that serves to bear witness, confirm, or authenticate; validation, verification, documentation.
> A confirmation or authentication.
> The process, performed by accountants or auditors, of providing independent opinion on published financial and other business information of a business, public agency, or other organization.
- [en.wiktionary.org](https://en.wiktionary.org/wiki/attestation)

### merriam-webster

> an act or instance of attesting something: such as
> - a proving of the existence of something through evidence
> - an official verification of something as true or authentic

- [merriam-webster](https://www.merriam-webster.com/dictionary/attestation)

---
-api-id: P:Windows.Security.Cryptography.Core.AsymmetricAlgorithmNames.RsaSignPkcs1Sha1
-api-type: winrt property
---

<!-- Property syntax
public string RsaSignPkcs1Sha1 { get; }
-->

# Windows.Security.Cryptography.Core.AsymmetricAlgorithmNames.RsaSignPkcs1Sha1

## -description
Retrieves a string that contains "RSASIGN_PKCS1_SHA1".

## -property-value
String that contains "RSASIGN_PKCS1_SHA1".

## -remarks
Use the string retrieved by this property to set the asymmetric algorithm name when you call the [OpenAlgorithm](asymmetrickeyalgorithmprovider_openalgorithm_637226074.md) method. The string represents an RSA signing algorithm that uses PKCS1 to pad the plaintext and the Secure Hashing Algorithm (SHA) to hash the message contents before signing. The length of the SHA hash is 160 bits.

## -examples

## -see-also
[AsymmetricKeyAlgorithmProvider](asymmetrickeyalgorithmprovider.md)
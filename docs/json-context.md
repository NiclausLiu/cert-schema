## Blockchain Certificates JSON LD Context

    {
      "@context": [
        {
          "id": "@id",
          "type": "@type",
          "bc": "https://w3id.org/blockcerts#",
          "obi": "https://w3id.org/openbadges#",
          "cp": "https://w3id.org/chainpoint#",
          "extensions": "https://w3id.org/openbadges/extensions#",
          "validation": "obi:validation",
          "xsd": "http://www.w3.org/2001/XMLSchema#",
          "schema": "http://schema.org/",
          "sec": "https://w3id.org/security#",
          "Assertion": "bc:Assertion",
          "Certificate": "bc:Certificate",
          "Issuer": "bc:Issuer",
          "BlockchainCertificate": "bc:BlockchainCertificate",
          "CertificateDocument": "bc:CertificateDocument",
          "issuer": {
            "@id": "bc:issuer",
            "@type": "@id"
          },
          "recipient": {
            "@id": "bc:recipient",
            "@type": "@id"
          },
          "blockchaincertificate": {
            "@id": "bc:blockchaincertificate",
            "@type": "@id"
          },
          "certificate": {
            "@id": "bc:certificate",
            "@type": "@id"
          },
          "document": {
            "@id": "bc:document",
            "@type": "@id"
          },
          "assertion": {
            "@id": "bc:assertion",
            "@type": "@id"
          },
          "verify": {
            "@id": "bc:verify",
            "@type": "@id"
          },
          "recipient": {
            "@id": "bc:recipient",
            "@type": "@id"
          },
          "receipt": {
            "@id": "bc:receipt",
            "@type": "@id"
          },
          "publicKey": {
            "@id": "bc:publicKey"
          },
          "revocationKey": {
            "@id": "bc:revocationKey"
          },
          "image:signature": {
            "@id": "bc:image:signature"
          },
          "signature": {
            "@id": "bc:signature"
          },
          "familyName": {
            "@id": "schema:familyName"
          },
          "givenName": {
            "@id": "schema:givenName"
          },
          "signer": {
            "@id": "bc:signer",
            "@type": "@id"
          },
          "attribute-signed": {
            "@id": "bc:attribute-signed"
          },
          "ECDSA(secp256k1)": "bc:SignedBadge",
          "subtitle": {
            "@id": "bc:subtitle"
          },
          "email": "schema:email",
          "hashed": {
            "@id": "obi:hashed",
            "@type": "xsd:boolean"
          },
          "image": {
            "@id": "schema:image",
            "@type": "@id"
          },
          "salt": {
            "@id": "obi:salt"
          },
          "identity": {
            "@id": "obi:identityHash"
          },
          "issuedOn": {
            "@id": "obi:issueDate",
            "@type": "xsd:dateTime"
          },
          "expires": {
            "@id": "sec:expiration",
            "@type": "xsd:dateTime"
          },
          "evidence": {
            "@id": "obi:evidence",
            "@type": "@id"
          },
          "criteria": {
            "@id": "obi:criteria",
            "@type": "@id"
          },
          "tags": {
            "@id": "schema:keywords"
          },
          "alignment": {
            "@id": "obi:alignment",
            "@type": "@id"
          },
          "revocationList": {
            "@id": "obi:revocationList",
            "@type": "@id"
          },
          "name": {
            "@id": "schema:name"
          },
          "description": {
            "@id": "schema:description"
          },
          "url": {
            "@id": "schema:url",
            "@type": "@id"
          },
          "uid": {
            "@id": "obi:uid"
          },
          "revocationList": "obi:revocationList",
          "TypeValidation": "obi:TypeValidation",
          "FrameValidation": "obi:FrameValidation",
          "validatesType": "obi:validatesType",
          "validationSchema": "obi:validationSchema",
          "validationFrame": "obi:validationFrame",
          "ChainpointSHA224v2": "cp:ChainpointSHA224v2",
          "ChainpointSHA256v2": "cp:ChainpointSHA256v2",
          "ChainpointSHA384v2": "cp:ChainpointSHA384v2",
          "ChainpointSHA512v2": "cp:ChainpointSHA512v2",
          "ChainpointSHA3-224v2": "cp:ChainpointSHA3-224v2",
          "ChainpointSHA3-256v2": "cp:ChainpointSHA3-256v2",
          "ChainpointSHA3-384v2": "cp:ChainpointSHA3-384v2",
          "ChainpointSHA3-512v2": "cp:ChainpointSHA3-512v2",
          "BTCOpReturn": "cp:BTCOpReturn",
          "targetHash": "cp:targetHash",
          "merkleRoot": "cp:merkleRoot",
          "proof": "cp:proof",
          "anchors": "cp:anchors",
          "sourceId": "cp:sourceId",
          "right": "cp:right",
          "left": "cp:left"
        }
      ],
      "validation": [
        {
          "type": "TypeValidation",
          "validatesType": "Assertion",
          "validationSchema": "http://w3id.org/blockcerts/schema/1.2/assertion-1.2.json"
        },
        {
          "type": "TypeValidation",
          "validatesType": "Certificate",
          "validationSchema": "http://w3id.org/blockcerts/schema/1.2/certificate-1.2.json"
        },
        {
          "type": "TypeValidation",
          "validatesType": "Issuer",
          "validationSchema": "http://w3id.org/blockcerts/schema/1.2/issuer-1.2.json"
        },
        {
          "type": "TypeValidation",
          "validatesType": "CertificateDocument",
          "validationSchema": "http://w3id.org/blockcerts/schema/1.2/certificate-document-1.2.json"
        },
        {
          "type": "TypeValidation",
          "validatesType": "BlockchainCertificate",
          "validationSchema": "http://w3id.org/blockcerts/schema/1.2/blockchain-certificate-1.2.json"
        },
        {
          "type": "TypeValidation",
          "validatesType": "BlockchainReceipt",
          "validationSchema": "http://w3id.org/blockcerts/schema/1.2/blockchain-receipt-1.2.json"
        }
      ]
    }

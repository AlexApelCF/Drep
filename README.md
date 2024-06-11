{
  "@context": {
    "@language": "en-us",
    "CIP100": "https://github.com/cardano-foundation/CIPs/blob/master/CIP-0100/README.md#",
    "CIPQQQ": "https://github.com/cardano-foundation/CIPs/blob/master/CIP-QQQ/README.md#",
    "hashAlgorithm": "CIP100:hashAlgorithm",
    "body": {
      "@id": "CIPQQQ:body",
      "@context": {
        "references": {
          "@id": "CIPQQQ:references",
          "@container": "@set",
          "@context": {
            "GovernanceMetadata": "CIP100:GovernanceMetadataReference",
            "Other": "CIP100:OtherReference",
            "label": "CIP100:reference-label",
            "uri": "CIP100:reference-uri",
            "referenceHash": {
              "@id": "CIPQQQ:referenceHash",
              "@context": {
                "hashDigest": "CIPQQQ:hashDigest",
                "hashAlgorithm": "CIP100:hashAlgorithm"
              }
            }
          }
        },
        "dRepName": "CIPQQQ:dRepName",
        "bio": "CIPQQQ:bio",
        "email": "CIPQQQ:email"
      }
    },
    "authors": {
      "@id": "CIP100:authors",
      "@container": "@set",
      "@context": {
        "name": "http://xmlns.com/foaf/0.1/name",
        "witness": {
          "@id": "CIP100:witness",
          "@context": {
            "witnessAlgorithm": "CIP100:witnessAlgorithm",
            "publicKey": "CIP100:publicKey",
            "signature": "CIP100:signature"
          }
        }
      }
    }
  },
  "authors": [],
  "hashAlgorithm": {
    "@value": "blake2b-256"
  },
  "body": {
    "bio": {
      "@value": "Just testing this tool"
    },
    "dRepName": {
      "@value": "Alextest"
    },
    "email": {
      "@value": "alex.apeldoorn@cardanofoundation.org"
    },
    "references": [
      {
        "@type": "Other",
        "CIPQQQ:reference-label": {
          "@value": "Label"
        },
        "CIPQQQ:reference-uri": {
          "@value": "Cardanofoundation.org"
        }
      }
    ]
  }
}

# go-entrust

### Description
Search certificate transparency (CT) logs using Entrust's API

### Usage
```
go run .\entrust-ct-search.go -domain acuereqol.org
```
### Output
Returns JSON
```
[
  {
    "logEntries": [
      {
        "logName": "rocketeer",
        "entryIndex": -1,
        "timestamp": 0
      },
      {
        "logName": "pilot",
        "entryIndex": -1,
        "timestamp": 0
      }
    ],
    "thumbprint": "7D8E4AFDA33C8E9AF791B92A4A3D1AF3C61A8E67",
    "issuerDN": "cn\u003dGo Daddy Secure Certificate Authority - G2,ou\u003dhttp://certs.godaddy.com/repository/,o\u003dGoDaddy.com, Inc.,l\u003dScottsdale,st\u003dArizona,c\u003dUS",
    "issuerCN": "Go Daddy Secure Certificate Authority - G2",
    "issuerO": "GoDaddy.com, Inc.",
    "sn": "15192541240151185280",
    "subjectDN": "cn\u003d*.acuereqol.org,ou\u003dDomain Control Validated",
    "subjectCNReversed": "gro.loqereuca.*",
    "validFrom": "2019-02-24T14:42:16Z",
    "validTo": "2021-04-25T18:25:53Z",
    "signAlg": "sha256WithRSAEncryption",
    "publicKeySize": 2048,
    "publicKeyType": "RSA",
    "ev": false,
    "san": [
      {
        "type": 2,
        "valueReversed": "gro.loqereuca.*"
      },
      {
        "type": 2,
        "valueReversed": "gro.loqereuca"
      }
    ]
  },
  {
    "logEntries": [
      {
        "logName": "rocketeer",
        "entryIndex": -1,
        "timestamp": 0
      },
      {
        "logName": "pilot",
        "entryIndex": -1,
        "timestamp": 0
      }
    ],
    "thumbprint": "261FA72927FE0B1826E2658C77F9267C542429DC",
    "issuerDN": "cn\u003dGo Daddy Secure Certificate Authority - G2,ou\u003dhttp://certs.godaddy.com/repository/,o\u003dGoDaddy.com, Inc.,l\u003dScottsdale,st\u003dArizona,c\u003dUS",
    "issuerCN": "Go Daddy Secure Certificate Authority - G2",
    "issuerO": "GoDaddy.com, Inc.",
    "sn": "8663085477365692237",
    "subjectDN": "cn\u003d*.acuereqol.org,ou\u003dDomain Control Validated",
    "subjectCNReversed": "gro.loqereuca.*",
    "validFrom": "2019-04-15T22:32:33Z",
    "validTo": "2021-04-25T18:25:53Z",
    "signAlg": "sha256WithRSAEncryption",
    "publicKeySize": 2048,
    "publicKeyType": "RSA",
    "ev": false,
    "san": [
      {
        "type": 2,
        "valueReversed": "gro.loqereuca.*"
      },
      {
        "type": 2,
        "valueReversed": "gro.loqereuca"
      }
    ]
  },
  {
    "logEntries": [
      {
        "logName": "pilot",
        "entryIndex": -1,
        "timestamp": 0
      },
      {
        "logName": "rocketeer",
        "entryIndex": -1,
        "timestamp": 0
      }
    ],
    "thumbprint": "9B2A5236E3A5139F7C18192B397101A07F5DEEED",
    "issuerDN": "cn\u003dGo Daddy Secure Certificate Authority - G2,ou\u003dhttp://certs.godaddy.com/repository/,o\u003dGoDaddy.com, Inc.,l\u003dScottsdale,st\u003dArizona,c\u003dUS",
    "issuerCN": "Go Daddy Secure Certificate Authority - G2",
    "issuerO": "GoDaddy.com, Inc.",
    "sn": "8663085477365692237",
    "subjectDN": "cn\u003d*.acuereqol.org,ou\u003dDomain Control Validated",
    "subjectCNReversed": "gro.loqereuca.*",
    "validFrom": "2019-04-15T22:32:33Z",
    "validTo": "2021-04-25T18:25:53Z",
    "signAlg": "sha256WithRSAEncryption",
    "publicKeySize": 2048,
    "publicKeyType": "RSA",
    "ev": false,
    "san": [
      {
        "type": 2,
        "valueReversed": "gro.loqereuca.*"
      },
      {
        "type": 2,
        "valueReversed": "gro.loqereuca"
      }
    ]
  }
]
```
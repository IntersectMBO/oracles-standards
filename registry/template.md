## Cardano Oracle Registry Template

| Field | Value |
|-------|-------|
| Project Name | [insert project name here] |
| Authorised Entity | [individual/company] |
| Role | Consumer / Provider |
| ADA/USD Payload Example | Price: $0.00<br>Time of retrieval: [date & time UTC]<br>Wire format: [insert cbor payload here] |
| (**optional**) Data reference per [CIP-57](https://cips.cardano.org/cip/CIP-57) | |
| How is this payload fed on-chain? | examples: "the serialised blob is set at the datum field of an output at a trusted script which is then referenced" or "the serialised blob is passed through the redeemer set". The more detail here the better! |
| References | [sdks, documentation, source reference of how to deserialise the payload] | 

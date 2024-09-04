| Field | Value |
|-------|-------|
| Project Name | Orcfax |
| Authorised Entity | Christian Koch |
| Role | Provider |
| ADA/USD Payload Example | The datum datatype is a parameterised datatype parameterised by the `body`. It is expressed in aiken lang as follows:<br><pre>pub type Statement<t> {<br>  feed_id : ByteArray,<br>  created_at : Int,<br>  body : t,<br>}</pre>For feeds of type current exchange rate (CER), the body is:<br><pre>pub type Rational {<br>  num: Int,<br>  denom: Int,<br>}</pre>More complete documentation can be found in our [docs](https://docs.orcfax.io/consume#coercing-fs-data) |
| (**optional**) Data reference per [CIP-57](https://cips.cardano.org/cip/CIP-57) |   |
| How is this payload fed on-chain? |  As the inlined datum of a UTXO with an identifiable token |
| References | * https://docs.orcfax.io/consume <br>* https://docs.orcfax.io/policies |

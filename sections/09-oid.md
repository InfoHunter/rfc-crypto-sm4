#  Object Identifier

The Object Identifier for SM4 is identified through these OIDs.

## GM/T OID

"1.2.156.10197.1.104" for "SM4 Algorithm" [@GMT-0006-2012].

## ISO OID

"1.0.18033.3.2.4" for "id-bc128-sm4" [@ISO.IEC.18033-3.AMD2],
described below.

```
is18033-3     OID ::= {iso(1) standard(0) is18033(18033) part3(3)}
id-bc128      OID ::= {is18033-3 block-cipher-128-bit(2)}
id-bc128-sm4  OID ::= {id-bc128 sm4(4)}
```
# Class: BizAccountPayload

Defined in: [WAProto/index.d.ts:990](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L990)

Represents a BizAccountPayload.

## Implements

- [`IBizAccountPayload`](../interfaces/IBizAccountPayload.md)

## Constructors

### new BizAccountPayload()

> **new BizAccountPayload**(`properties`?): [`BizAccountPayload`](BizAccountPayload.md)

Defined in: [WAProto/index.d.ts:996](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L996)

Constructs a new BizAccountPayload.

#### Parameters

##### properties?

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md)

Properties to set

#### Returns

[`BizAccountPayload`](BizAccountPayload.md)

## Properties

### bizAcctLinkInfo

> **bizAcctLinkInfo**: `Uint8Array`

Defined in: [WAProto/index.d.ts:1002](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1002)

BizAccountPayload bizAcctLinkInfo.

#### Implementation of

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md).[`bizAcctLinkInfo`](../interfaces/IBizAccountPayload.md#bizacctlinkinfo)

***

### vnameCert?

> `optional` **vnameCert**: `null` \| [`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:999](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L999)

BizAccountPayload vnameCert.

#### Implementation of

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md).[`vnameCert`](../interfaces/IBizAccountPayload.md#vnamecert)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1072](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1072)

Converts this BizAccountPayload to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BizAccountPayload`](BizAccountPayload.md)

Defined in: [WAProto/index.d.ts:1009](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1009)

Creates a new BizAccountPayload instance using the specified properties.

#### Parameters

##### properties?

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md)

Properties to set

#### Returns

[`BizAccountPayload`](BizAccountPayload.md)

BizAccountPayload instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BizAccountPayload`](BizAccountPayload.md)

Defined in: [WAProto/index.d.ts:1035](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1035)

Decodes a BizAccountPayload message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BizAccountPayload`](BizAccountPayload.md)

BizAccountPayload

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BizAccountPayload`](BizAccountPayload.md)

Defined in: [WAProto/index.d.ts:1044](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1044)

Decodes a BizAccountPayload message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BizAccountPayload`](BizAccountPayload.md)

BizAccountPayload

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1017](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1017)

Encodes the specified BizAccountPayload message. Does not implicitly [verify](BizAccountPayload.md#verify) messages.

#### Parameters

##### message

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md)

BizAccountPayload message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1025](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1025)

Encodes the specified BizAccountPayload message, length delimited. Does not implicitly [verify](BizAccountPayload.md#verify) messages.

#### Parameters

##### message

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md)

BizAccountPayload message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BizAccountPayload`](BizAccountPayload.md)

Defined in: [WAProto/index.d.ts:1058](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1058)

Creates a BizAccountPayload message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BizAccountPayload`](BizAccountPayload.md)

BizAccountPayload

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:1066](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1066)

Creates a plain object from a BizAccountPayload message. Also converts values to other types if specified.

#### Parameters

##### message

[`BizAccountPayload`](BizAccountPayload.md)

BizAccountPayload

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1051](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1051)

Verifies a BizAccountPayload message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

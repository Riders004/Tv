# Class: ReportingTokenInfo

Defined in: [WAProto/index.d.ts:27350](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27350)

Represents a ReportingTokenInfo.

## Implements

- [`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

## Constructors

### new ReportingTokenInfo()

> **new ReportingTokenInfo**(`properties`?): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:27356](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27356)

Constructs a new ReportingTokenInfo.

#### Parameters

##### properties?

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

Properties to set

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

## Properties

### reportingTag

> **reportingTag**: `Uint8Array`

Defined in: [WAProto/index.d.ts:27359](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27359)

ReportingTokenInfo reportingTag.

#### Implementation of

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md).[`reportingTag`](../interfaces/IReportingTokenInfo.md#reportingtag)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27429](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27429)

Converts this ReportingTokenInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:27366](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27366)

Creates a new ReportingTokenInfo instance using the specified properties.

#### Parameters

##### properties?

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

Properties to set

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:27392](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27392)

Decodes a ReportingTokenInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:27401](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27401)

Decodes a ReportingTokenInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27374](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27374)

Encodes the specified ReportingTokenInfo message. Does not implicitly [verify](ReportingTokenInfo.md#verify) messages.

#### Parameters

##### message

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

ReportingTokenInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27382](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27382)

Encodes the specified ReportingTokenInfo message, length delimited. Does not implicitly [verify](ReportingTokenInfo.md#verify) messages.

#### Parameters

##### message

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

ReportingTokenInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:27415](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27415)

Creates a ReportingTokenInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:27423](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27423)

Creates a plain object from a ReportingTokenInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27408](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L27408)

Verifies a ReportingTokenInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

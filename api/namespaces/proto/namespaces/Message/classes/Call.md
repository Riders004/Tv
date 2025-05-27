# Class: Call

Defined in: [WAProto/index.d.ts:11811](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11811)

Represents a Call.

## Implements

- [`ICall`](../interfaces/ICall.md)

## Constructors

### new Call()

> **new Call**(`properties`?): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:11817](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11817)

Constructs a new Call.

#### Parameters

##### properties?

[`ICall`](../interfaces/ICall.md)

Properties to set

#### Returns

[`Call`](Call.md)

## Properties

### callKey

> **callKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:11820](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11820)

Call callKey.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`callKey`](../interfaces/ICall.md#callkey)

***

### conversionData

> **conversionData**: `Uint8Array`

Defined in: [WAProto/index.d.ts:11826](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11826)

Call conversionData.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`conversionData`](../interfaces/ICall.md#conversiondata)

***

### conversionDelaySeconds

> **conversionDelaySeconds**: `number`

Defined in: [WAProto/index.d.ts:11829](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11829)

Call conversionDelaySeconds.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`conversionDelaySeconds`](../interfaces/ICall.md#conversiondelayseconds)

***

### conversionSource

> **conversionSource**: `string`

Defined in: [WAProto/index.d.ts:11823](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11823)

Call conversionSource.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`conversionSource`](../interfaces/ICall.md#conversionsource)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11899](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11899)

Converts this Call to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:11836](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11836)

Creates a new Call instance using the specified properties.

#### Parameters

##### properties?

[`ICall`](../interfaces/ICall.md)

Properties to set

#### Returns

[`Call`](Call.md)

Call instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:11862](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11862)

Decodes a Call message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Call`](Call.md)

Call

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:11871](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11871)

Decodes a Call message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Call`](Call.md)

Call

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11844](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11844)

Encodes the specified Call message. Does not implicitly [verify](Call.md#verify) messages.

#### Parameters

##### message

[`ICall`](../interfaces/ICall.md)

Call message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11852](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11852)

Encodes the specified Call message, length delimited. Does not implicitly [verify](Call.md#verify) messages.

#### Parameters

##### message

[`ICall`](../interfaces/ICall.md)

Call message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:11885](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11885)

Creates a Call message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Call`](Call.md)

Call

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:11893](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11893)

Creates a plain object from a Call message. Also converts values to other types if specified.

#### Parameters

##### message

[`Call`](Call.md)

Call

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11878](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11878)

Verifies a Call message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

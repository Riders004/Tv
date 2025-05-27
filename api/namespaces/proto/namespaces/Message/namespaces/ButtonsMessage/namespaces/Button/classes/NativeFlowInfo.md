# Class: NativeFlowInfo

Defined in: [WAProto/index.d.ts:11569](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11569)

Represents a NativeFlowInfo.

## Implements

- [`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

## Constructors

### new NativeFlowInfo()

> **new NativeFlowInfo**(`properties`?): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:11575](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11575)

Constructs a new NativeFlowInfo.

#### Parameters

##### properties?

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

Properties to set

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

## Properties

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:11578](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11578)

NativeFlowInfo name.

#### Implementation of

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md).[`name`](../interfaces/INativeFlowInfo.md#name)

***

### paramsJson

> **paramsJson**: `string`

Defined in: [WAProto/index.d.ts:11581](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11581)

NativeFlowInfo paramsJson.

#### Implementation of

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md).[`paramsJson`](../interfaces/INativeFlowInfo.md#paramsjson)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11651](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11651)

Converts this NativeFlowInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:11588](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11588)

Creates a new NativeFlowInfo instance using the specified properties.

#### Parameters

##### properties?

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

Properties to set

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:11614](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11614)

Decodes a NativeFlowInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:11623](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11623)

Decodes a NativeFlowInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11596](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11596)

Encodes the specified NativeFlowInfo message. Does not implicitly [verify](NativeFlowInfo.md#verify) messages.

#### Parameters

##### message

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

NativeFlowInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11604)

Encodes the specified NativeFlowInfo message, length delimited. Does not implicitly [verify](NativeFlowInfo.md#verify) messages.

#### Parameters

##### message

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

NativeFlowInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:11637](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11637)

Creates a NativeFlowInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:11645](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11645)

Creates a plain object from a NativeFlowInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11630](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11630)

Verifies a NativeFlowInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

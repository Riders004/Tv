# Class: PushNameSetting

Defined in: [WAProto/index.d.ts:32895](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32895)

Represents a PushNameSetting.

## Implements

- [`IPushNameSetting`](../interfaces/IPushNameSetting.md)

## Constructors

### new PushNameSetting()

> **new PushNameSetting**(`properties`?): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:32901](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32901)

Constructs a new PushNameSetting.

#### Parameters

##### properties?

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

Properties to set

#### Returns

[`PushNameSetting`](PushNameSetting.md)

## Properties

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:32904](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32904)

PushNameSetting name.

#### Implementation of

[`IPushNameSetting`](../interfaces/IPushNameSetting.md).[`name`](../interfaces/IPushNameSetting.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32974](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32974)

Converts this PushNameSetting to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:32911](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32911)

Creates a new PushNameSetting instance using the specified properties.

#### Parameters

##### properties?

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

Properties to set

#### Returns

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:32937](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32937)

Decodes a PushNameSetting message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:32946](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32946)

Decodes a PushNameSetting message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32919](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32919)

Encodes the specified PushNameSetting message. Does not implicitly [verify](PushNameSetting.md#verify) messages.

#### Parameters

##### message

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

PushNameSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32927](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32927)

Encodes the specified PushNameSetting message, length delimited. Does not implicitly [verify](PushNameSetting.md#verify) messages.

#### Parameters

##### message

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

PushNameSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:32960](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32960)

Creates a PushNameSetting message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32968](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32968)

Creates a plain object from a PushNameSetting message. Also converts values to other types if specified.

#### Parameters

##### message

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32953](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32953)

Verifies a PushNameSetting message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

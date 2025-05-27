# Class: Pushname

Defined in: [WAProto/index.d.ts:26538](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26538)

Represents a Pushname.

## Implements

- [`IPushname`](../interfaces/IPushname.md)

## Constructors

### new Pushname()

> **new Pushname**(`properties`?): [`Pushname`](Pushname.md)

Defined in: [WAProto/index.d.ts:26544](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26544)

Constructs a new Pushname.

#### Parameters

##### properties?

[`IPushname`](../interfaces/IPushname.md)

Properties to set

#### Returns

[`Pushname`](Pushname.md)

## Properties

### id

> **id**: `string`

Defined in: [WAProto/index.d.ts:26547](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26547)

Pushname id.

#### Implementation of

[`IPushname`](../interfaces/IPushname.md).[`id`](../interfaces/IPushname.md#id)

***

### pushname

> **pushname**: `string`

Defined in: [WAProto/index.d.ts:26550](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26550)

Pushname pushname.

#### Implementation of

[`IPushname`](../interfaces/IPushname.md).[`pushname`](../interfaces/IPushname.md#pushname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26620](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26620)

Converts this Pushname to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Pushname`](Pushname.md)

Defined in: [WAProto/index.d.ts:26557](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26557)

Creates a new Pushname instance using the specified properties.

#### Parameters

##### properties?

[`IPushname`](../interfaces/IPushname.md)

Properties to set

#### Returns

[`Pushname`](Pushname.md)

Pushname instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Pushname`](Pushname.md)

Defined in: [WAProto/index.d.ts:26583](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26583)

Decodes a Pushname message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Pushname`](Pushname.md)

Pushname

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Pushname`](Pushname.md)

Defined in: [WAProto/index.d.ts:26592](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26592)

Decodes a Pushname message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Pushname`](Pushname.md)

Pushname

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26565](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26565)

Encodes the specified Pushname message. Does not implicitly [verify](Pushname.md#verify) messages.

#### Parameters

##### message

[`IPushname`](../interfaces/IPushname.md)

Pushname message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26573](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26573)

Encodes the specified Pushname message, length delimited. Does not implicitly [verify](Pushname.md#verify) messages.

#### Parameters

##### message

[`IPushname`](../interfaces/IPushname.md)

Pushname message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Pushname`](Pushname.md)

Defined in: [WAProto/index.d.ts:26606](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26606)

Creates a Pushname message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Pushname`](Pushname.md)

Pushname

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:26614](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26614)

Creates a plain object from a Pushname message. Also converts values to other types if specified.

#### Parameters

##### message

[`Pushname`](Pushname.md)

Pushname

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26599](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L26599)

Verifies a Pushname message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

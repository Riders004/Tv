# Class: CollectionMessage

Defined in: [WAProto/index.d.ts:15858](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15858)

Represents a CollectionMessage.

## Implements

- [`ICollectionMessage`](../interfaces/ICollectionMessage.md)

## Constructors

### new CollectionMessage()

> **new CollectionMessage**(`properties`?): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:15864](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15864)

Constructs a new CollectionMessage.

#### Parameters

##### properties?

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

Properties to set

#### Returns

[`CollectionMessage`](CollectionMessage.md)

## Properties

### bizJid

> **bizJid**: `string`

Defined in: [WAProto/index.d.ts:15867](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15867)

CollectionMessage bizJid.

#### Implementation of

[`ICollectionMessage`](../interfaces/ICollectionMessage.md).[`bizJid`](../interfaces/ICollectionMessage.md#bizjid)

***

### id

> **id**: `string`

Defined in: [WAProto/index.d.ts:15870](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15870)

CollectionMessage id.

#### Implementation of

[`ICollectionMessage`](../interfaces/ICollectionMessage.md).[`id`](../interfaces/ICollectionMessage.md#id)

***

### messageVersion

> **messageVersion**: `number`

Defined in: [WAProto/index.d.ts:15873](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15873)

CollectionMessage messageVersion.

#### Implementation of

[`ICollectionMessage`](../interfaces/ICollectionMessage.md).[`messageVersion`](../interfaces/ICollectionMessage.md#messageversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15943](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15943)

Converts this CollectionMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:15880](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15880)

Creates a new CollectionMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

Properties to set

#### Returns

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:15906](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15906)

Decodes a CollectionMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:15915](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15915)

Decodes a CollectionMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15888](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15888)

Encodes the specified CollectionMessage message. Does not implicitly [verify](CollectionMessage.md#verify) messages.

#### Parameters

##### message

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

CollectionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15896](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15896)

Encodes the specified CollectionMessage message, length delimited. Does not implicitly [verify](CollectionMessage.md#verify) messages.

#### Parameters

##### message

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

CollectionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:15929](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15929)

Creates a CollectionMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:15937](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15937)

Creates a plain object from a CollectionMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:15922](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15922)

Verifies a CollectionMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

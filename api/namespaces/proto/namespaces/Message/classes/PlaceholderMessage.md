# Class: PlaceholderMessage

Defined in: [WAProto/index.d.ts:20032](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20032)

Represents a PlaceholderMessage.

## Implements

- [`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md)

## Constructors

### new PlaceholderMessage()

> **new PlaceholderMessage**(`properties`?): [`PlaceholderMessage`](PlaceholderMessage.md)

Defined in: [WAProto/index.d.ts:20038](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20038)

Constructs a new PlaceholderMessage.

#### Parameters

##### properties?

[`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md)

Properties to set

#### Returns

[`PlaceholderMessage`](PlaceholderMessage.md)

## Properties

### type

> **type**: [`MASK_LINKED_DEVICES`](../namespaces/PlaceholderMessage/enumerations/PlaceholderType.md#mask_linked_devices)

Defined in: [WAProto/index.d.ts:20041](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20041)

PlaceholderMessage type.

#### Implementation of

[`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md).[`type`](../interfaces/IPlaceholderMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20111](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20111)

Converts this PlaceholderMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PlaceholderMessage`](PlaceholderMessage.md)

Defined in: [WAProto/index.d.ts:20048](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20048)

Creates a new PlaceholderMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md)

Properties to set

#### Returns

[`PlaceholderMessage`](PlaceholderMessage.md)

PlaceholderMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PlaceholderMessage`](PlaceholderMessage.md)

Defined in: [WAProto/index.d.ts:20074](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20074)

Decodes a PlaceholderMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PlaceholderMessage`](PlaceholderMessage.md)

PlaceholderMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PlaceholderMessage`](PlaceholderMessage.md)

Defined in: [WAProto/index.d.ts:20083](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20083)

Decodes a PlaceholderMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PlaceholderMessage`](PlaceholderMessage.md)

PlaceholderMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20056](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20056)

Encodes the specified PlaceholderMessage message. Does not implicitly [verify](PlaceholderMessage.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md)

PlaceholderMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20064](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20064)

Encodes the specified PlaceholderMessage message, length delimited. Does not implicitly [verify](PlaceholderMessage.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md)

PlaceholderMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PlaceholderMessage`](PlaceholderMessage.md)

Defined in: [WAProto/index.d.ts:20097](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20097)

Creates a PlaceholderMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PlaceholderMessage`](PlaceholderMessage.md)

PlaceholderMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:20105](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20105)

Creates a plain object from a PlaceholderMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PlaceholderMessage`](PlaceholderMessage.md)

PlaceholderMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20090](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L20090)

Verifies a PlaceholderMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

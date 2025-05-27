# Class: ContactMessage

Defined in: [WAProto/index.d.ts:12430](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12430)

Represents a ContactMessage.

## Implements

- [`IContactMessage`](../interfaces/IContactMessage.md)

## Constructors

### new ContactMessage()

> **new ContactMessage**(`properties`?): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:12436](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12436)

Constructs a new ContactMessage.

#### Parameters

##### properties?

[`IContactMessage`](../interfaces/IContactMessage.md)

Properties to set

#### Returns

[`ContactMessage`](ContactMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:12445](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12445)

ContactMessage contextInfo.

#### Implementation of

[`IContactMessage`](../interfaces/IContactMessage.md).[`contextInfo`](../interfaces/IContactMessage.md#contextinfo)

***

### displayName

> **displayName**: `string`

Defined in: [WAProto/index.d.ts:12439](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12439)

ContactMessage displayName.

#### Implementation of

[`IContactMessage`](../interfaces/IContactMessage.md).[`displayName`](../interfaces/IContactMessage.md#displayname)

***

### vcard

> **vcard**: `string`

Defined in: [WAProto/index.d.ts:12442](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12442)

ContactMessage vcard.

#### Implementation of

[`IContactMessage`](../interfaces/IContactMessage.md).[`vcard`](../interfaces/IContactMessage.md#vcard)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12515](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12515)

Converts this ContactMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:12452](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12452)

Creates a new ContactMessage instance using the specified properties.

#### Parameters

##### properties?

[`IContactMessage`](../interfaces/IContactMessage.md)

Properties to set

#### Returns

[`ContactMessage`](ContactMessage.md)

ContactMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:12478](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12478)

Decodes a ContactMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ContactMessage`](ContactMessage.md)

ContactMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:12487](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12487)

Decodes a ContactMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ContactMessage`](ContactMessage.md)

ContactMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12460](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12460)

Encodes the specified ContactMessage message. Does not implicitly [verify](ContactMessage.md#verify) messages.

#### Parameters

##### message

[`IContactMessage`](../interfaces/IContactMessage.md)

ContactMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12468](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12468)

Encodes the specified ContactMessage message, length delimited. Does not implicitly [verify](ContactMessage.md#verify) messages.

#### Parameters

##### message

[`IContactMessage`](../interfaces/IContactMessage.md)

ContactMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:12501](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12501)

Creates a ContactMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ContactMessage`](ContactMessage.md)

ContactMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:12509](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12509)

Creates a plain object from a ContactMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ContactMessage`](ContactMessage.md)

ContactMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12494](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12494)

Verifies a ContactMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

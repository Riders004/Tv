# Class: ContactsArrayMessage

Defined in: [WAProto/index.d.ts:12532](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12532)

Represents a ContactsArrayMessage.

## Implements

- [`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

## Constructors

### new ContactsArrayMessage()

> **new ContactsArrayMessage**(`properties`?): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:12538](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12538)

Constructs a new ContactsArrayMessage.

#### Parameters

##### properties?

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

Properties to set

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

## Properties

### contacts

> **contacts**: [`IContactMessage`](../interfaces/IContactMessage.md)[]

Defined in: [WAProto/index.d.ts:12544](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12544)

ContactsArrayMessage contacts.

#### Implementation of

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md).[`contacts`](../interfaces/IContactsArrayMessage.md#contacts)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:12547](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12547)

ContactsArrayMessage contextInfo.

#### Implementation of

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md).[`contextInfo`](../interfaces/IContactsArrayMessage.md#contextinfo)

***

### displayName

> **displayName**: `string`

Defined in: [WAProto/index.d.ts:12541](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12541)

ContactsArrayMessage displayName.

#### Implementation of

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md).[`displayName`](../interfaces/IContactsArrayMessage.md#displayname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12617](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12617)

Converts this ContactsArrayMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:12554](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12554)

Creates a new ContactsArrayMessage instance using the specified properties.

#### Parameters

##### properties?

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

Properties to set

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:12580](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12580)

Decodes a ContactsArrayMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:12589](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12589)

Decodes a ContactsArrayMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12562](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12562)

Encodes the specified ContactsArrayMessage message. Does not implicitly [verify](ContactsArrayMessage.md#verify) messages.

#### Parameters

##### message

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

ContactsArrayMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12570](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12570)

Encodes the specified ContactsArrayMessage message, length delimited. Does not implicitly [verify](ContactsArrayMessage.md#verify) messages.

#### Parameters

##### message

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

ContactsArrayMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:12603](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12603)

Creates a ContactsArrayMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:12611](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12611)

Creates a plain object from a ContactsArrayMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12596](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12596)

Verifies a ContactsArrayMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

# Class: ContactAction

Defined in: [WAProto/index.d.ts:30604](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30604)

Represents a ContactAction.

## Implements

- [`IContactAction`](../interfaces/IContactAction.md)

## Constructors

### new ContactAction()

> **new ContactAction**(`properties`?): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:30610](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30610)

Constructs a new ContactAction.

#### Parameters

##### properties?

[`IContactAction`](../interfaces/IContactAction.md)

Properties to set

#### Returns

[`ContactAction`](ContactAction.md)

## Properties

### firstName

> **firstName**: `string`

Defined in: [WAProto/index.d.ts:30616](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30616)

ContactAction firstName.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`firstName`](../interfaces/IContactAction.md#firstname)

***

### fullName

> **fullName**: `string`

Defined in: [WAProto/index.d.ts:30613](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30613)

ContactAction fullName.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`fullName`](../interfaces/IContactAction.md#fullname)

***

### lidJid

> **lidJid**: `string`

Defined in: [WAProto/index.d.ts:30619](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30619)

ContactAction lidJid.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`lidJid`](../interfaces/IContactAction.md#lidjid)

***

### saveOnPrimaryAddressbook

> **saveOnPrimaryAddressbook**: `boolean`

Defined in: [WAProto/index.d.ts:30622](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30622)

ContactAction saveOnPrimaryAddressbook.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`saveOnPrimaryAddressbook`](../interfaces/IContactAction.md#saveonprimaryaddressbook)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30692](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30692)

Converts this ContactAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:30629](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30629)

Creates a new ContactAction instance using the specified properties.

#### Parameters

##### properties?

[`IContactAction`](../interfaces/IContactAction.md)

Properties to set

#### Returns

[`ContactAction`](ContactAction.md)

ContactAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:30655](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30655)

Decodes a ContactAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ContactAction`](ContactAction.md)

ContactAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:30664](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30664)

Decodes a ContactAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ContactAction`](ContactAction.md)

ContactAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30637](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30637)

Encodes the specified ContactAction message. Does not implicitly [verify](ContactAction.md#verify) messages.

#### Parameters

##### message

[`IContactAction`](../interfaces/IContactAction.md)

ContactAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30645](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30645)

Encodes the specified ContactAction message, length delimited. Does not implicitly [verify](ContactAction.md#verify) messages.

#### Parameters

##### message

[`IContactAction`](../interfaces/IContactAction.md)

ContactAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:30678](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30678)

Creates a ContactAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ContactAction`](ContactAction.md)

ContactAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:30686](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30686)

Creates a plain object from a ContactAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`ContactAction`](ContactAction.md)

ContactAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30671](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30671)

Verifies a ContactAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

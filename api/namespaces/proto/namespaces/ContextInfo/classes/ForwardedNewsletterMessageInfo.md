# Class: ForwardedNewsletterMessageInfo

Defined in: [WAProto/index.d.ts:4923](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4923)

Represents a ForwardedNewsletterMessageInfo.

## Implements

- [`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

## Constructors

### new ForwardedNewsletterMessageInfo()

> **new ForwardedNewsletterMessageInfo**(`properties`?): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:4929](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4929)

Constructs a new ForwardedNewsletterMessageInfo.

#### Parameters

##### properties?

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

Properties to set

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

## Properties

### accessibilityText

> **accessibilityText**: `string`

Defined in: [WAProto/index.d.ts:4944](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4944)

ForwardedNewsletterMessageInfo accessibilityText.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`accessibilityText`](../interfaces/IForwardedNewsletterMessageInfo.md#accessibilitytext)

***

### contentType

> **contentType**: [`ContentType`](../namespaces/ForwardedNewsletterMessageInfo/enumerations/ContentType.md)

Defined in: [WAProto/index.d.ts:4941](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4941)

ForwardedNewsletterMessageInfo contentType.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`contentType`](../interfaces/IForwardedNewsletterMessageInfo.md#contenttype)

***

### newsletterJid

> **newsletterJid**: `string`

Defined in: [WAProto/index.d.ts:4932](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4932)

ForwardedNewsletterMessageInfo newsletterJid.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`newsletterJid`](../interfaces/IForwardedNewsletterMessageInfo.md#newsletterjid)

***

### newsletterName

> **newsletterName**: `string`

Defined in: [WAProto/index.d.ts:4938](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4938)

ForwardedNewsletterMessageInfo newsletterName.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`newsletterName`](../interfaces/IForwardedNewsletterMessageInfo.md#newslettername)

***

### serverMessageId

> **serverMessageId**: `number`

Defined in: [WAProto/index.d.ts:4935](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4935)

ForwardedNewsletterMessageInfo serverMessageId.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`serverMessageId`](../interfaces/IForwardedNewsletterMessageInfo.md#servermessageid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5014](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5014)

Converts this ForwardedNewsletterMessageInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:4951](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4951)

Creates a new ForwardedNewsletterMessageInfo instance using the specified properties.

#### Parameters

##### properties?

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

Properties to set

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:4977](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4977)

Decodes a ForwardedNewsletterMessageInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:4986](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4986)

Decodes a ForwardedNewsletterMessageInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4959](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4959)

Encodes the specified ForwardedNewsletterMessageInfo message. Does not implicitly [verify](ForwardedNewsletterMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4967](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4967)

Encodes the specified ForwardedNewsletterMessageInfo message, length delimited. Does not implicitly [verify](ForwardedNewsletterMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:5000](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5000)

Creates a ForwardedNewsletterMessageInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:5008](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5008)

Creates a plain object from a ForwardedNewsletterMessageInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4993](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L4993)

Verifies a ForwardedNewsletterMessageInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

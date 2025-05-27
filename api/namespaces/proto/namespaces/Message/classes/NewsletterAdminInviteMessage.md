# Class: NewsletterAdminInviteMessage

Defined in: [WAProto/index.d.ts:18445](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18445)

Represents a NewsletterAdminInviteMessage.

## Implements

- [`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

## Constructors

### new NewsletterAdminInviteMessage()

> **new NewsletterAdminInviteMessage**(`properties`?): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:18451](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18451)

Constructs a new NewsletterAdminInviteMessage.

#### Parameters

##### properties?

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

Properties to set

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

## Properties

### caption

> **caption**: `string`

Defined in: [WAProto/index.d.ts:18463](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18463)

NewsletterAdminInviteMessage caption.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`caption`](../interfaces/INewsletterAdminInviteMessage.md#caption)

***

### inviteExpiration

> **inviteExpiration**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:18466](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18466)

NewsletterAdminInviteMessage inviteExpiration.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`inviteExpiration`](../interfaces/INewsletterAdminInviteMessage.md#inviteexpiration)

***

### jpegThumbnail

> **jpegThumbnail**: `Uint8Array`

Defined in: [WAProto/index.d.ts:18460](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18460)

NewsletterAdminInviteMessage jpegThumbnail.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`jpegThumbnail`](../interfaces/INewsletterAdminInviteMessage.md#jpegthumbnail)

***

### newsletterJid

> **newsletterJid**: `string`

Defined in: [WAProto/index.d.ts:18454](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18454)

NewsletterAdminInviteMessage newsletterJid.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`newsletterJid`](../interfaces/INewsletterAdminInviteMessage.md#newsletterjid)

***

### newsletterName

> **newsletterName**: `string`

Defined in: [WAProto/index.d.ts:18457](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18457)

NewsletterAdminInviteMessage newsletterName.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`newsletterName`](../interfaces/INewsletterAdminInviteMessage.md#newslettername)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:18536](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18536)

Converts this NewsletterAdminInviteMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:18473](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18473)

Creates a new NewsletterAdminInviteMessage instance using the specified properties.

#### Parameters

##### properties?

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

Properties to set

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:18499](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18499)

Decodes a NewsletterAdminInviteMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:18508](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18508)

Decodes a NewsletterAdminInviteMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18481](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18481)

Encodes the specified NewsletterAdminInviteMessage message. Does not implicitly [verify](NewsletterAdminInviteMessage.md#verify) messages.

#### Parameters

##### message

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18489](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18489)

Encodes the specified NewsletterAdminInviteMessage message, length delimited. Does not implicitly [verify](NewsletterAdminInviteMessage.md#verify) messages.

#### Parameters

##### message

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:18522](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18522)

Creates a NewsletterAdminInviteMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:18530](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18530)

Creates a plain object from a NewsletterAdminInviteMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:18515](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L18515)

Verifies a NewsletterAdminInviteMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

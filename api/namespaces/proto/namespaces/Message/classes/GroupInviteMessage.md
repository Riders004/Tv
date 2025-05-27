# Class: GroupInviteMessage

Defined in: [WAProto/index.d.ts:14220](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14220)

Represents a GroupInviteMessage.

## Implements

- [`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

## Constructors

### new GroupInviteMessage()

> **new GroupInviteMessage**(`properties`?): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:14226](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14226)

Constructs a new GroupInviteMessage.

#### Parameters

##### properties?

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

Properties to set

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

## Properties

### caption

> **caption**: `string`

Defined in: [WAProto/index.d.ts:14244](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14244)

GroupInviteMessage caption.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`caption`](../interfaces/IGroupInviteMessage.md#caption)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:14247](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14247)

GroupInviteMessage contextInfo.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`contextInfo`](../interfaces/IGroupInviteMessage.md#contextinfo)

***

### groupJid

> **groupJid**: `string`

Defined in: [WAProto/index.d.ts:14229](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14229)

GroupInviteMessage groupJid.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`groupJid`](../interfaces/IGroupInviteMessage.md#groupjid)

***

### groupName

> **groupName**: `string`

Defined in: [WAProto/index.d.ts:14238](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14238)

GroupInviteMessage groupName.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`groupName`](../interfaces/IGroupInviteMessage.md#groupname)

***

### groupType

> **groupType**: [`GroupType`](../namespaces/GroupInviteMessage/enumerations/GroupType.md)

Defined in: [WAProto/index.d.ts:14250](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14250)

GroupInviteMessage groupType.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`groupType`](../interfaces/IGroupInviteMessage.md#grouptype)

***

### inviteCode

> **inviteCode**: `string`

Defined in: [WAProto/index.d.ts:14232](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14232)

GroupInviteMessage inviteCode.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`inviteCode`](../interfaces/IGroupInviteMessage.md#invitecode)

***

### inviteExpiration

> **inviteExpiration**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:14235](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14235)

GroupInviteMessage inviteExpiration.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`inviteExpiration`](../interfaces/IGroupInviteMessage.md#inviteexpiration)

***

### jpegThumbnail

> **jpegThumbnail**: `Uint8Array`

Defined in: [WAProto/index.d.ts:14241](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14241)

GroupInviteMessage jpegThumbnail.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`jpegThumbnail`](../interfaces/IGroupInviteMessage.md#jpegthumbnail)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14320](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14320)

Converts this GroupInviteMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:14257](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14257)

Creates a new GroupInviteMessage instance using the specified properties.

#### Parameters

##### properties?

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

Properties to set

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:14283](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14283)

Decodes a GroupInviteMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:14292](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14292)

Decodes a GroupInviteMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14265](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14265)

Encodes the specified GroupInviteMessage message. Does not implicitly [verify](GroupInviteMessage.md#verify) messages.

#### Parameters

##### message

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

GroupInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14273](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14273)

Encodes the specified GroupInviteMessage message, length delimited. Does not implicitly [verify](GroupInviteMessage.md#verify) messages.

#### Parameters

##### message

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

GroupInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:14306](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14306)

Creates a GroupInviteMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:14314](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14314)

Creates a plain object from a GroupInviteMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14299](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L14299)

Verifies a GroupInviteMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

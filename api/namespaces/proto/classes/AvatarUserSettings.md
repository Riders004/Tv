# Class: AvatarUserSettings

Defined in: [WAProto/index.d.ts:766](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L766)

Represents an AvatarUserSettings.

## Implements

- [`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md)

## Constructors

### new AvatarUserSettings()

> **new AvatarUserSettings**(`properties`?): [`AvatarUserSettings`](AvatarUserSettings.md)

Defined in: [WAProto/index.d.ts:772](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L772)

Constructs a new AvatarUserSettings.

#### Parameters

##### properties?

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md)

Properties to set

#### Returns

[`AvatarUserSettings`](AvatarUserSettings.md)

## Properties

### fbid

> **fbid**: `string`

Defined in: [WAProto/index.d.ts:775](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L775)

AvatarUserSettings fbid.

#### Implementation of

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md).[`fbid`](../interfaces/IAvatarUserSettings.md#fbid)

***

### password

> **password**: `string`

Defined in: [WAProto/index.d.ts:778](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L778)

AvatarUserSettings password.

#### Implementation of

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md).[`password`](../interfaces/IAvatarUserSettings.md#password)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:848](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L848)

Converts this AvatarUserSettings to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AvatarUserSettings`](AvatarUserSettings.md)

Defined in: [WAProto/index.d.ts:785](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L785)

Creates a new AvatarUserSettings instance using the specified properties.

#### Parameters

##### properties?

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md)

Properties to set

#### Returns

[`AvatarUserSettings`](AvatarUserSettings.md)

AvatarUserSettings instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AvatarUserSettings`](AvatarUserSettings.md)

Defined in: [WAProto/index.d.ts:811](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L811)

Decodes an AvatarUserSettings message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AvatarUserSettings`](AvatarUserSettings.md)

AvatarUserSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AvatarUserSettings`](AvatarUserSettings.md)

Defined in: [WAProto/index.d.ts:820](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L820)

Decodes an AvatarUserSettings message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AvatarUserSettings`](AvatarUserSettings.md)

AvatarUserSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:793](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L793)

Encodes the specified AvatarUserSettings message. Does not implicitly [verify](AvatarUserSettings.md#verify) messages.

#### Parameters

##### message

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md)

AvatarUserSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:801](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L801)

Encodes the specified AvatarUserSettings message, length delimited. Does not implicitly [verify](AvatarUserSettings.md#verify) messages.

#### Parameters

##### message

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md)

AvatarUserSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AvatarUserSettings`](AvatarUserSettings.md)

Defined in: [WAProto/index.d.ts:834](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L834)

Creates an AvatarUserSettings message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AvatarUserSettings`](AvatarUserSettings.md)

AvatarUserSettings

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:842](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L842)

Creates a plain object from an AvatarUserSettings message. Also converts values to other types if specified.

#### Parameters

##### message

[`AvatarUserSettings`](AvatarUserSettings.md)

AvatarUserSettings

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:827](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L827)

Verifies an AvatarUserSettings message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

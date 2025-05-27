# Class: WallpaperSettings

Defined in: [WAProto/index.d.ts:35837](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35837)

Represents a WallpaperSettings.

## Implements

- [`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

## Constructors

### new WallpaperSettings()

> **new WallpaperSettings**(`properties`?): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:35843](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35843)

Constructs a new WallpaperSettings.

#### Parameters

##### properties?

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

Properties to set

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

## Properties

### filename

> **filename**: `string`

Defined in: [WAProto/index.d.ts:35846](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35846)

WallpaperSettings filename.

#### Implementation of

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md).[`filename`](../interfaces/IWallpaperSettings.md#filename)

***

### opacity

> **opacity**: `number`

Defined in: [WAProto/index.d.ts:35849](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35849)

WallpaperSettings opacity.

#### Implementation of

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md).[`opacity`](../interfaces/IWallpaperSettings.md#opacity)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35919](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35919)

Converts this WallpaperSettings to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:35856](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35856)

Creates a new WallpaperSettings instance using the specified properties.

#### Parameters

##### properties?

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

Properties to set

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:35882](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35882)

Decodes a WallpaperSettings message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:35891](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35891)

Decodes a WallpaperSettings message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35864](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35864)

Encodes the specified WallpaperSettings message. Does not implicitly [verify](WallpaperSettings.md#verify) messages.

#### Parameters

##### message

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

WallpaperSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35872](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35872)

Encodes the specified WallpaperSettings message, length delimited. Does not implicitly [verify](WallpaperSettings.md#verify) messages.

#### Parameters

##### message

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

WallpaperSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:35905](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35905)

Creates a WallpaperSettings message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:35913](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35913)

Creates a plain object from a WallpaperSettings message. Also converts values to other types if specified.

#### Parameters

##### message

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35898](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35898)

Verifies a WallpaperSettings message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

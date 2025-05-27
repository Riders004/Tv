# Class: AutoDownloadSettings

Defined in: [WAProto/index.d.ts:664](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L664)

Represents an AutoDownloadSettings.

## Implements

- [`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

## Constructors

### new AutoDownloadSettings()

> **new AutoDownloadSettings**(`properties`?): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:670](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L670)

Constructs a new AutoDownloadSettings.

#### Parameters

##### properties?

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

Properties to set

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

## Properties

### downloadAudio

> **downloadAudio**: `boolean`

Defined in: [WAProto/index.d.ts:676](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L676)

AutoDownloadSettings downloadAudio.

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadAudio`](../interfaces/IAutoDownloadSettings.md#downloadaudio)

***

### downloadDocuments

> **downloadDocuments**: `boolean`

Defined in: [WAProto/index.d.ts:682](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L682)

AutoDownloadSettings downloadDocuments.

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadDocuments`](../interfaces/IAutoDownloadSettings.md#downloaddocuments)

***

### downloadImages

> **downloadImages**: `boolean`

Defined in: [WAProto/index.d.ts:673](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L673)

AutoDownloadSettings downloadImages.

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadImages`](../interfaces/IAutoDownloadSettings.md#downloadimages)

***

### downloadVideo

> **downloadVideo**: `boolean`

Defined in: [WAProto/index.d.ts:679](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L679)

AutoDownloadSettings downloadVideo.

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadVideo`](../interfaces/IAutoDownloadSettings.md#downloadvideo)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:752](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L752)

Converts this AutoDownloadSettings to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:689](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L689)

Creates a new AutoDownloadSettings instance using the specified properties.

#### Parameters

##### properties?

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

Properties to set

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:715](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L715)

Decodes an AutoDownloadSettings message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L724)

Decodes an AutoDownloadSettings message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:697](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L697)

Encodes the specified AutoDownloadSettings message. Does not implicitly [verify](AutoDownloadSettings.md#verify) messages.

#### Parameters

##### message

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

AutoDownloadSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:705](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L705)

Encodes the specified AutoDownloadSettings message, length delimited. Does not implicitly [verify](AutoDownloadSettings.md#verify) messages.

#### Parameters

##### message

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

AutoDownloadSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:738](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L738)

Creates an AutoDownloadSettings message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:746](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L746)

Creates a plain object from an AutoDownloadSettings message. Also converts values to other types if specified.

#### Parameters

##### message

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:731](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L731)

Verifies an AutoDownloadSettings message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

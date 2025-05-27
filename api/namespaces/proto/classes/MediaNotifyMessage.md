# Class: MediaNotifyMessage

Defined in: [WAProto/index.d.ts:9400](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9400)

Represents a MediaNotifyMessage.

## Implements

- [`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md)

## Constructors

### new MediaNotifyMessage()

> **new MediaNotifyMessage**(`properties`?): [`MediaNotifyMessage`](MediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:9406](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9406)

Constructs a new MediaNotifyMessage.

#### Parameters

##### properties?

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md)

Properties to set

#### Returns

[`MediaNotifyMessage`](MediaNotifyMessage.md)

## Properties

### expressPathUrl

> **expressPathUrl**: `string`

Defined in: [WAProto/index.d.ts:9409](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9409)

MediaNotifyMessage expressPathUrl.

#### Implementation of

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md).[`expressPathUrl`](../interfaces/IMediaNotifyMessage.md#expresspathurl)

***

### fileEncSha256

> **fileEncSha256**: `Uint8Array`

Defined in: [WAProto/index.d.ts:9412](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9412)

MediaNotifyMessage fileEncSha256.

#### Implementation of

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md).[`fileEncSha256`](../interfaces/IMediaNotifyMessage.md#fileencsha256)

***

### fileLength

> **fileLength**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:9415](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9415)

MediaNotifyMessage fileLength.

#### Implementation of

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md).[`fileLength`](../interfaces/IMediaNotifyMessage.md#filelength)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9485](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9485)

Converts this MediaNotifyMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MediaNotifyMessage`](MediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:9422](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9422)

Creates a new MediaNotifyMessage instance using the specified properties.

#### Parameters

##### properties?

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md)

Properties to set

#### Returns

[`MediaNotifyMessage`](MediaNotifyMessage.md)

MediaNotifyMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MediaNotifyMessage`](MediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:9448](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9448)

Decodes a MediaNotifyMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MediaNotifyMessage`](MediaNotifyMessage.md)

MediaNotifyMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MediaNotifyMessage`](MediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:9457](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9457)

Decodes a MediaNotifyMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MediaNotifyMessage`](MediaNotifyMessage.md)

MediaNotifyMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9430](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9430)

Encodes the specified MediaNotifyMessage message. Does not implicitly [verify](MediaNotifyMessage.md#verify) messages.

#### Parameters

##### message

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md)

MediaNotifyMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9438](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9438)

Encodes the specified MediaNotifyMessage message, length delimited. Does not implicitly [verify](MediaNotifyMessage.md#verify) messages.

#### Parameters

##### message

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md)

MediaNotifyMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MediaNotifyMessage`](MediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:9471](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9471)

Creates a MediaNotifyMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MediaNotifyMessage`](MediaNotifyMessage.md)

MediaNotifyMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:9479](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9479)

Creates a plain object from a MediaNotifyMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`MediaNotifyMessage`](MediaNotifyMessage.md)

MediaNotifyMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:9464](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L9464)

Verifies a MediaNotifyMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

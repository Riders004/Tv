# Class: DeviceSentMessage

Defined in: [WAProto/index.d.ts:12724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12724)

Represents a DeviceSentMessage.

## Implements

- [`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

## Constructors

### new DeviceSentMessage()

> **new DeviceSentMessage**(`properties`?): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:12730](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12730)

Constructs a new DeviceSentMessage.

#### Parameters

##### properties?

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

Properties to set

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

## Properties

### destinationJid

> **destinationJid**: `string`

Defined in: [WAProto/index.d.ts:12733](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12733)

DeviceSentMessage destinationJid.

#### Implementation of

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md).[`destinationJid`](../interfaces/IDeviceSentMessage.md#destinationjid)

***

### message?

> `optional` **message**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:12736](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12736)

DeviceSentMessage message.

#### Implementation of

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md).[`message`](../interfaces/IDeviceSentMessage.md#message)

***

### phash

> **phash**: `string`

Defined in: [WAProto/index.d.ts:12739](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12739)

DeviceSentMessage phash.

#### Implementation of

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md).[`phash`](../interfaces/IDeviceSentMessage.md#phash)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12809](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12809)

Converts this DeviceSentMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:12746](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12746)

Creates a new DeviceSentMessage instance using the specified properties.

#### Parameters

##### properties?

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

Properties to set

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:12772](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12772)

Decodes a DeviceSentMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:12781](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12781)

Decodes a DeviceSentMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12754](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12754)

Encodes the specified DeviceSentMessage message. Does not implicitly [verify](DeviceSentMessage.md#verify) messages.

#### Parameters

##### message

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

DeviceSentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12762](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12762)

Encodes the specified DeviceSentMessage message, length delimited. Does not implicitly [verify](DeviceSentMessage.md#verify) messages.

#### Parameters

##### message

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

DeviceSentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:12795](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12795)

Creates a DeviceSentMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:12803](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12803)

Creates a plain object from a DeviceSentMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12788](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12788)

Verifies a DeviceSentMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

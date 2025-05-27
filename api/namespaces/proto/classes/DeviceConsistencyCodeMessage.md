# Class: DeviceConsistencyCodeMessage

Defined in: [WAProto/index.d.ts:5499](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5499)

Represents a DeviceConsistencyCodeMessage.

## Implements

- [`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

## Constructors

### new DeviceConsistencyCodeMessage()

> **new DeviceConsistencyCodeMessage**(`properties`?): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:5505](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5505)

Constructs a new DeviceConsistencyCodeMessage.

#### Parameters

##### properties?

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

Properties to set

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

## Properties

### generation

> **generation**: `number`

Defined in: [WAProto/index.d.ts:5508](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5508)

DeviceConsistencyCodeMessage generation.

#### Implementation of

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md).[`generation`](../interfaces/IDeviceConsistencyCodeMessage.md#generation)

***

### signature

> **signature**: `Uint8Array`

Defined in: [WAProto/index.d.ts:5511](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5511)

DeviceConsistencyCodeMessage signature.

#### Implementation of

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md).[`signature`](../interfaces/IDeviceConsistencyCodeMessage.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5581](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5581)

Converts this DeviceConsistencyCodeMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:5518](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5518)

Creates a new DeviceConsistencyCodeMessage instance using the specified properties.

#### Parameters

##### properties?

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

Properties to set

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:5544](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5544)

Decodes a DeviceConsistencyCodeMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:5553](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5553)

Decodes a DeviceConsistencyCodeMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5526](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5526)

Encodes the specified DeviceConsistencyCodeMessage message. Does not implicitly [verify](DeviceConsistencyCodeMessage.md#verify) messages.

#### Parameters

##### message

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5534](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5534)

Encodes the specified DeviceConsistencyCodeMessage message, length delimited. Does not implicitly [verify](DeviceConsistencyCodeMessage.md#verify) messages.

#### Parameters

##### message

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:5567](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5567)

Creates a DeviceConsistencyCodeMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:5575](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5575)

Creates a plain object from a DeviceConsistencyCodeMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5560](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5560)

Verifies a DeviceConsistencyCodeMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

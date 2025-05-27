# Class: DeviceListMetadata

Defined in: [WAProto/index.d.ts:5613](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5613)

Represents a DeviceListMetadata.

## Implements

- [`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

## Constructors

### new DeviceListMetadata()

> **new DeviceListMetadata**(`properties`?): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:5619](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5619)

Constructs a new DeviceListMetadata.

#### Parameters

##### properties?

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

Properties to set

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

## Properties

### receiverAccountType

> **receiverAccountType**: [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:5634](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5634)

DeviceListMetadata receiverAccountType.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`receiverAccountType`](../interfaces/IDeviceListMetadata.md#receiveraccounttype)

***

### recipientKeyHash

> **recipientKeyHash**: `Uint8Array`

Defined in: [WAProto/index.d.ts:5637](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5637)

DeviceListMetadata recipientKeyHash.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`recipientKeyHash`](../interfaces/IDeviceListMetadata.md#recipientkeyhash)

***

### recipientKeyIndexes

> **recipientKeyIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:5643](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5643)

DeviceListMetadata recipientKeyIndexes.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`recipientKeyIndexes`](../interfaces/IDeviceListMetadata.md#recipientkeyindexes)

***

### recipientTimestamp

> **recipientTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:5640](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5640)

DeviceListMetadata recipientTimestamp.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`recipientTimestamp`](../interfaces/IDeviceListMetadata.md#recipienttimestamp)

***

### senderAccountType

> **senderAccountType**: [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:5631](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5631)

DeviceListMetadata senderAccountType.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderAccountType`](../interfaces/IDeviceListMetadata.md#senderaccounttype)

***

### senderKeyHash

> **senderKeyHash**: `Uint8Array`

Defined in: [WAProto/index.d.ts:5622](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5622)

DeviceListMetadata senderKeyHash.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderKeyHash`](../interfaces/IDeviceListMetadata.md#senderkeyhash)

***

### senderKeyIndexes

> **senderKeyIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:5628](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5628)

DeviceListMetadata senderKeyIndexes.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderKeyIndexes`](../interfaces/IDeviceListMetadata.md#senderkeyindexes)

***

### senderTimestamp

> **senderTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:5625](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5625)

DeviceListMetadata senderTimestamp.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderTimestamp`](../interfaces/IDeviceListMetadata.md#sendertimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5713](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5713)

Converts this DeviceListMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:5650](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5650)

Creates a new DeviceListMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

Properties to set

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:5676](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5676)

Decodes a DeviceListMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:5685](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5685)

Decodes a DeviceListMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5658](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5658)

Encodes the specified DeviceListMetadata message. Does not implicitly [verify](DeviceListMetadata.md#verify) messages.

#### Parameters

##### message

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

DeviceListMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5666](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5666)

Encodes the specified DeviceListMetadata message, length delimited. Does not implicitly [verify](DeviceListMetadata.md#verify) messages.

#### Parameters

##### message

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

DeviceListMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:5699](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5699)

Creates a DeviceListMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:5707](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5707)

Creates a plain object from a DeviceListMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5692](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5692)

Verifies a DeviceListMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

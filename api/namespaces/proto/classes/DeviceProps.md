# Class: DeviceProps

Defined in: [WAProto/index.d.ts:5736](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5736)

Represents a DeviceProps.

## Implements

- [`IDeviceProps`](../interfaces/IDeviceProps.md)

## Constructors

### new DeviceProps()

> **new DeviceProps**(`properties`?): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:5742](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5742)

Constructs a new DeviceProps.

#### Parameters

##### properties?

[`IDeviceProps`](../interfaces/IDeviceProps.md)

Properties to set

#### Returns

[`DeviceProps`](DeviceProps.md)

## Properties

### historySyncConfig?

> `optional` **historySyncConfig**: `null` \| [`IHistorySyncConfig`](../namespaces/DeviceProps/interfaces/IHistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:5757](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5757)

DeviceProps historySyncConfig.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`historySyncConfig`](../interfaces/IDeviceProps.md#historysyncconfig)

***

### os

> **os**: `string`

Defined in: [WAProto/index.d.ts:5745](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5745)

DeviceProps os.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`os`](../interfaces/IDeviceProps.md#os)

***

### platformType

> **platformType**: [`PlatformType`](../namespaces/DeviceProps/enumerations/PlatformType.md)

Defined in: [WAProto/index.d.ts:5751](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5751)

DeviceProps platformType.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`platformType`](../interfaces/IDeviceProps.md#platformtype)

***

### requireFullSync

> **requireFullSync**: `boolean`

Defined in: [WAProto/index.d.ts:5754](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5754)

DeviceProps requireFullSync.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`requireFullSync`](../interfaces/IDeviceProps.md#requirefullsync)

***

### version?

> `optional` **version**: `null` \| [`IAppVersion`](../namespaces/DeviceProps/interfaces/IAppVersion.md)

Defined in: [WAProto/index.d.ts:5748](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5748)

DeviceProps version.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`version`](../interfaces/IDeviceProps.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5827](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5827)

Converts this DeviceProps to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:5764](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5764)

Creates a new DeviceProps instance using the specified properties.

#### Parameters

##### properties?

[`IDeviceProps`](../interfaces/IDeviceProps.md)

Properties to set

#### Returns

[`DeviceProps`](DeviceProps.md)

DeviceProps instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:5790](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5790)

Decodes a DeviceProps message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeviceProps`](DeviceProps.md)

DeviceProps

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:5799](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5799)

Decodes a DeviceProps message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeviceProps`](DeviceProps.md)

DeviceProps

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5772](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5772)

Encodes the specified DeviceProps message. Does not implicitly [verify](DeviceProps.md#verify) messages.

#### Parameters

##### message

[`IDeviceProps`](../interfaces/IDeviceProps.md)

DeviceProps message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5780](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5780)

Encodes the specified DeviceProps message, length delimited. Does not implicitly [verify](DeviceProps.md#verify) messages.

#### Parameters

##### message

[`IDeviceProps`](../interfaces/IDeviceProps.md)

DeviceProps message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:5813](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5813)

Creates a DeviceProps message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeviceProps`](DeviceProps.md)

DeviceProps

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:5821](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5821)

Creates a plain object from a DeviceProps message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeviceProps`](DeviceProps.md)

DeviceProps

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5806](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5806)

Verifies a DeviceProps message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

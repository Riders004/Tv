# Class: WebInfo

Defined in: [WAProto/index.d.ts:3793](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3793)

Represents a WebInfo.

## Implements

- [`IWebInfo`](../interfaces/IWebInfo.md)

## Constructors

### new WebInfo()

> **new WebInfo**(`properties`?): [`WebInfo`](WebInfo.md)

Defined in: [WAProto/index.d.ts:3799](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3799)

Constructs a new WebInfo.

#### Parameters

##### properties?

[`IWebInfo`](../interfaces/IWebInfo.md)

Properties to set

#### Returns

[`WebInfo`](WebInfo.md)

## Properties

### refToken

> **refToken**: `string`

Defined in: [WAProto/index.d.ts:3802](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3802)

WebInfo refToken.

#### Implementation of

[`IWebInfo`](../interfaces/IWebInfo.md).[`refToken`](../interfaces/IWebInfo.md#reftoken)

***

### version

> **version**: `string`

Defined in: [WAProto/index.d.ts:3805](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3805)

WebInfo version.

#### Implementation of

[`IWebInfo`](../interfaces/IWebInfo.md).[`version`](../interfaces/IWebInfo.md#version)

***

### webdPayload?

> `optional` **webdPayload**: `null` \| [`IWebdPayload`](../namespaces/WebInfo/interfaces/IWebdPayload.md)

Defined in: [WAProto/index.d.ts:3808](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3808)

WebInfo webdPayload.

#### Implementation of

[`IWebInfo`](../interfaces/IWebInfo.md).[`webdPayload`](../interfaces/IWebInfo.md#webdpayload)

***

### webSubPlatform

> **webSubPlatform**: [`WebSubPlatform`](../namespaces/WebInfo/enumerations/WebSubPlatform.md)

Defined in: [WAProto/index.d.ts:3811](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3811)

WebInfo webSubPlatform.

#### Implementation of

[`IWebInfo`](../interfaces/IWebInfo.md).[`webSubPlatform`](../interfaces/IWebInfo.md#websubplatform)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3881](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3881)

Converts this WebInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`WebInfo`](WebInfo.md)

Defined in: [WAProto/index.d.ts:3818](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3818)

Creates a new WebInfo instance using the specified properties.

#### Parameters

##### properties?

[`IWebInfo`](../interfaces/IWebInfo.md)

Properties to set

#### Returns

[`WebInfo`](WebInfo.md)

WebInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`WebInfo`](WebInfo.md)

Defined in: [WAProto/index.d.ts:3844](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3844)

Decodes a WebInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`WebInfo`](WebInfo.md)

WebInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`WebInfo`](WebInfo.md)

Defined in: [WAProto/index.d.ts:3853](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3853)

Decodes a WebInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`WebInfo`](WebInfo.md)

WebInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3826](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3826)

Encodes the specified WebInfo message. Does not implicitly [verify](WebInfo.md#verify) messages.

#### Parameters

##### message

[`IWebInfo`](../interfaces/IWebInfo.md)

WebInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3834](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3834)

Encodes the specified WebInfo message, length delimited. Does not implicitly [verify](WebInfo.md#verify) messages.

#### Parameters

##### message

[`IWebInfo`](../interfaces/IWebInfo.md)

WebInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`WebInfo`](WebInfo.md)

Defined in: [WAProto/index.d.ts:3867](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3867)

Creates a WebInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`WebInfo`](WebInfo.md)

WebInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:3875](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3875)

Creates a plain object from a WebInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`WebInfo`](WebInfo.md)

WebInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3860](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3860)

Verifies a WebInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

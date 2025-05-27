# Class: ShopMessage

Defined in: [WAProto/index.d.ts:16386](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16386)

Represents a ShopMessage.

## Implements

- [`IShopMessage`](../interfaces/IShopMessage.md)

## Constructors

### new ShopMessage()

> **new ShopMessage**(`properties`?): [`ShopMessage`](ShopMessage.md)

Defined in: [WAProto/index.d.ts:16392](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16392)

Constructs a new ShopMessage.

#### Parameters

##### properties?

[`IShopMessage`](../interfaces/IShopMessage.md)

Properties to set

#### Returns

[`ShopMessage`](ShopMessage.md)

## Properties

### id

> **id**: `string`

Defined in: [WAProto/index.d.ts:16395](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16395)

ShopMessage id.

#### Implementation of

[`IShopMessage`](../interfaces/IShopMessage.md).[`id`](../interfaces/IShopMessage.md#id)

***

### messageVersion

> **messageVersion**: `number`

Defined in: [WAProto/index.d.ts:16401](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16401)

ShopMessage messageVersion.

#### Implementation of

[`IShopMessage`](../interfaces/IShopMessage.md).[`messageVersion`](../interfaces/IShopMessage.md#messageversion)

***

### surface

> **surface**: [`Surface`](../namespaces/ShopMessage/enumerations/Surface.md)

Defined in: [WAProto/index.d.ts:16398](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16398)

ShopMessage surface.

#### Implementation of

[`IShopMessage`](../interfaces/IShopMessage.md).[`surface`](../interfaces/IShopMessage.md#surface)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16471](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16471)

Converts this ShopMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ShopMessage`](ShopMessage.md)

Defined in: [WAProto/index.d.ts:16408](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16408)

Creates a new ShopMessage instance using the specified properties.

#### Parameters

##### properties?

[`IShopMessage`](../interfaces/IShopMessage.md)

Properties to set

#### Returns

[`ShopMessage`](ShopMessage.md)

ShopMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ShopMessage`](ShopMessage.md)

Defined in: [WAProto/index.d.ts:16434](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16434)

Decodes a ShopMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ShopMessage`](ShopMessage.md)

ShopMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ShopMessage`](ShopMessage.md)

Defined in: [WAProto/index.d.ts:16443](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16443)

Decodes a ShopMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ShopMessage`](ShopMessage.md)

ShopMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16416](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16416)

Encodes the specified ShopMessage message. Does not implicitly [verify](ShopMessage.md#verify) messages.

#### Parameters

##### message

[`IShopMessage`](../interfaces/IShopMessage.md)

ShopMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16424](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16424)

Encodes the specified ShopMessage message, length delimited. Does not implicitly [verify](ShopMessage.md#verify) messages.

#### Parameters

##### message

[`IShopMessage`](../interfaces/IShopMessage.md)

ShopMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ShopMessage`](ShopMessage.md)

Defined in: [WAProto/index.d.ts:16457](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16457)

Creates a ShopMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ShopMessage`](ShopMessage.md)

ShopMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:16465](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16465)

Creates a plain object from a ShopMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ShopMessage`](ShopMessage.md)

ShopMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16450](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L16450)

Verifies a ShopMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

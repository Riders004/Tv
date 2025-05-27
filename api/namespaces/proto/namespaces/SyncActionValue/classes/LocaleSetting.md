# Class: LocaleSetting

Defined in: [WAProto/index.d.ts:31753](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31753)

Represents a LocaleSetting.

## Implements

- [`ILocaleSetting`](../interfaces/ILocaleSetting.md)

## Constructors

### new LocaleSetting()

> **new LocaleSetting**(`properties`?): [`LocaleSetting`](LocaleSetting.md)

Defined in: [WAProto/index.d.ts:31759](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31759)

Constructs a new LocaleSetting.

#### Parameters

##### properties?

[`ILocaleSetting`](../interfaces/ILocaleSetting.md)

Properties to set

#### Returns

[`LocaleSetting`](LocaleSetting.md)

## Properties

### locale

> **locale**: `string`

Defined in: [WAProto/index.d.ts:31762](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31762)

LocaleSetting locale.

#### Implementation of

[`ILocaleSetting`](../interfaces/ILocaleSetting.md).[`locale`](../interfaces/ILocaleSetting.md#locale)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31832](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31832)

Converts this LocaleSetting to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LocaleSetting`](LocaleSetting.md)

Defined in: [WAProto/index.d.ts:31769](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31769)

Creates a new LocaleSetting instance using the specified properties.

#### Parameters

##### properties?

[`ILocaleSetting`](../interfaces/ILocaleSetting.md)

Properties to set

#### Returns

[`LocaleSetting`](LocaleSetting.md)

LocaleSetting instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LocaleSetting`](LocaleSetting.md)

Defined in: [WAProto/index.d.ts:31795](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31795)

Decodes a LocaleSetting message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LocaleSetting`](LocaleSetting.md)

LocaleSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LocaleSetting`](LocaleSetting.md)

Defined in: [WAProto/index.d.ts:31804](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31804)

Decodes a LocaleSetting message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LocaleSetting`](LocaleSetting.md)

LocaleSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31777](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31777)

Encodes the specified LocaleSetting message. Does not implicitly [verify](LocaleSetting.md#verify) messages.

#### Parameters

##### message

[`ILocaleSetting`](../interfaces/ILocaleSetting.md)

LocaleSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31785](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31785)

Encodes the specified LocaleSetting message, length delimited. Does not implicitly [verify](LocaleSetting.md#verify) messages.

#### Parameters

##### message

[`ILocaleSetting`](../interfaces/ILocaleSetting.md)

LocaleSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LocaleSetting`](LocaleSetting.md)

Defined in: [WAProto/index.d.ts:31818](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31818)

Creates a LocaleSetting message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LocaleSetting`](LocaleSetting.md)

LocaleSetting

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:31826](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31826)

Creates a plain object from a LocaleSetting message. Also converts values to other types if specified.

#### Parameters

##### message

[`LocaleSetting`](LocaleSetting.md)

LocaleSetting

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31811](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31811)

Verifies a LocaleSetting message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

# Class: StarAction

Defined in: [WAProto/index.d.ts:33369](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33369)

Represents a StarAction.

## Implements

- [`IStarAction`](../interfaces/IStarAction.md)

## Constructors

### new StarAction()

> **new StarAction**(`properties`?): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:33375](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33375)

Constructs a new StarAction.

#### Parameters

##### properties?

[`IStarAction`](../interfaces/IStarAction.md)

Properties to set

#### Returns

[`StarAction`](StarAction.md)

## Properties

### starred

> **starred**: `boolean`

Defined in: [WAProto/index.d.ts:33378](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33378)

StarAction starred.

#### Implementation of

[`IStarAction`](../interfaces/IStarAction.md).[`starred`](../interfaces/IStarAction.md#starred)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33448](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33448)

Converts this StarAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:33385](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33385)

Creates a new StarAction instance using the specified properties.

#### Parameters

##### properties?

[`IStarAction`](../interfaces/IStarAction.md)

Properties to set

#### Returns

[`StarAction`](StarAction.md)

StarAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:33411](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33411)

Decodes a StarAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StarAction`](StarAction.md)

StarAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:33420](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33420)

Decodes a StarAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StarAction`](StarAction.md)

StarAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33393](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33393)

Encodes the specified StarAction message. Does not implicitly [verify](StarAction.md#verify) messages.

#### Parameters

##### message

[`IStarAction`](../interfaces/IStarAction.md)

StarAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33401](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33401)

Encodes the specified StarAction message, length delimited. Does not implicitly [verify](StarAction.md#verify) messages.

#### Parameters

##### message

[`IStarAction`](../interfaces/IStarAction.md)

StarAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:33434](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33434)

Creates a StarAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StarAction`](StarAction.md)

StarAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33442](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33442)

Creates a plain object from a StarAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`StarAction`](StarAction.md)

StarAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33427](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33427)

Verifies a StarAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

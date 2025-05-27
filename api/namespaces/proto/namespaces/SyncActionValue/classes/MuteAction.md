# Class: MuteAction

Defined in: [WAProto/index.d.ts:32169](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32169)

Represents a MuteAction.

## Implements

- [`IMuteAction`](../interfaces/IMuteAction.md)

## Constructors

### new MuteAction()

> **new MuteAction**(`properties`?): [`MuteAction`](MuteAction.md)

Defined in: [WAProto/index.d.ts:32175](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32175)

Constructs a new MuteAction.

#### Parameters

##### properties?

[`IMuteAction`](../interfaces/IMuteAction.md)

Properties to set

#### Returns

[`MuteAction`](MuteAction.md)

## Properties

### autoMuted

> **autoMuted**: `boolean`

Defined in: [WAProto/index.d.ts:32184](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32184)

MuteAction autoMuted.

#### Implementation of

[`IMuteAction`](../interfaces/IMuteAction.md).[`autoMuted`](../interfaces/IMuteAction.md#automuted)

***

### muted

> **muted**: `boolean`

Defined in: [WAProto/index.d.ts:32178](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32178)

MuteAction muted.

#### Implementation of

[`IMuteAction`](../interfaces/IMuteAction.md).[`muted`](../interfaces/IMuteAction.md#muted)

***

### muteEndTimestamp

> **muteEndTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:32181](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32181)

MuteAction muteEndTimestamp.

#### Implementation of

[`IMuteAction`](../interfaces/IMuteAction.md).[`muteEndTimestamp`](../interfaces/IMuteAction.md#muteendtimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32254](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32254)

Converts this MuteAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MuteAction`](MuteAction.md)

Defined in: [WAProto/index.d.ts:32191](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32191)

Creates a new MuteAction instance using the specified properties.

#### Parameters

##### properties?

[`IMuteAction`](../interfaces/IMuteAction.md)

Properties to set

#### Returns

[`MuteAction`](MuteAction.md)

MuteAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MuteAction`](MuteAction.md)

Defined in: [WAProto/index.d.ts:32217](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32217)

Decodes a MuteAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MuteAction`](MuteAction.md)

MuteAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MuteAction`](MuteAction.md)

Defined in: [WAProto/index.d.ts:32226](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32226)

Decodes a MuteAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MuteAction`](MuteAction.md)

MuteAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32199](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32199)

Encodes the specified MuteAction message. Does not implicitly [verify](MuteAction.md#verify) messages.

#### Parameters

##### message

[`IMuteAction`](../interfaces/IMuteAction.md)

MuteAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32207](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32207)

Encodes the specified MuteAction message, length delimited. Does not implicitly [verify](MuteAction.md#verify) messages.

#### Parameters

##### message

[`IMuteAction`](../interfaces/IMuteAction.md)

MuteAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MuteAction`](MuteAction.md)

Defined in: [WAProto/index.d.ts:32240](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32240)

Creates a MuteAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MuteAction`](MuteAction.md)

MuteAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32248](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32248)

Creates a plain object from a MuteAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`MuteAction`](MuteAction.md)

MuteAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32233](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32233)

Verifies a MuteAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

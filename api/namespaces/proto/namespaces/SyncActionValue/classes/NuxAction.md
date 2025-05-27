# Class: NuxAction

Defined in: [WAProto/index.d.ts:32265](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32265)

Represents a NuxAction.

## Implements

- [`INuxAction`](../interfaces/INuxAction.md)

## Constructors

### new NuxAction()

> **new NuxAction**(`properties`?): [`NuxAction`](NuxAction.md)

Defined in: [WAProto/index.d.ts:32271](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32271)

Constructs a new NuxAction.

#### Parameters

##### properties?

[`INuxAction`](../interfaces/INuxAction.md)

Properties to set

#### Returns

[`NuxAction`](NuxAction.md)

## Properties

### acknowledged

> **acknowledged**: `boolean`

Defined in: [WAProto/index.d.ts:32274](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32274)

NuxAction acknowledged.

#### Implementation of

[`INuxAction`](../interfaces/INuxAction.md).[`acknowledged`](../interfaces/INuxAction.md#acknowledged)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32344](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32344)

Converts this NuxAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NuxAction`](NuxAction.md)

Defined in: [WAProto/index.d.ts:32281](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32281)

Creates a new NuxAction instance using the specified properties.

#### Parameters

##### properties?

[`INuxAction`](../interfaces/INuxAction.md)

Properties to set

#### Returns

[`NuxAction`](NuxAction.md)

NuxAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NuxAction`](NuxAction.md)

Defined in: [WAProto/index.d.ts:32307](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32307)

Decodes a NuxAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NuxAction`](NuxAction.md)

NuxAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NuxAction`](NuxAction.md)

Defined in: [WAProto/index.d.ts:32316](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32316)

Decodes a NuxAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NuxAction`](NuxAction.md)

NuxAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32289](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32289)

Encodes the specified NuxAction message. Does not implicitly [verify](NuxAction.md#verify) messages.

#### Parameters

##### message

[`INuxAction`](../interfaces/INuxAction.md)

NuxAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32297](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32297)

Encodes the specified NuxAction message, length delimited. Does not implicitly [verify](NuxAction.md#verify) messages.

#### Parameters

##### message

[`INuxAction`](../interfaces/INuxAction.md)

NuxAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NuxAction`](NuxAction.md)

Defined in: [WAProto/index.d.ts:32330](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32330)

Creates a NuxAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NuxAction`](NuxAction.md)

NuxAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32338](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32338)

Creates a plain object from a NuxAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`NuxAction`](NuxAction.md)

NuxAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32323](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32323)

Verifies a NuxAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

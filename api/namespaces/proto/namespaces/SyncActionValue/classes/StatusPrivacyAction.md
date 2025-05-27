# Class: StatusPrivacyAction

Defined in: [WAProto/index.d.ts:33462](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33462)

Represents a StatusPrivacyAction.

## Implements

- [`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

## Constructors

### new StatusPrivacyAction()

> **new StatusPrivacyAction**(`properties`?): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:33468](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33468)

Constructs a new StatusPrivacyAction.

#### Parameters

##### properties?

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

Properties to set

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

## Properties

### mode

> **mode**: [`StatusDistributionMode`](../namespaces/StatusPrivacyAction/enumerations/StatusDistributionMode.md)

Defined in: [WAProto/index.d.ts:33471](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33471)

StatusPrivacyAction mode.

#### Implementation of

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md).[`mode`](../interfaces/IStatusPrivacyAction.md#mode)

***

### userJid

> **userJid**: `string`[]

Defined in: [WAProto/index.d.ts:33474](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33474)

StatusPrivacyAction userJid.

#### Implementation of

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md).[`userJid`](../interfaces/IStatusPrivacyAction.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33544](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33544)

Converts this StatusPrivacyAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:33481](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33481)

Creates a new StatusPrivacyAction instance using the specified properties.

#### Parameters

##### properties?

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

Properties to set

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:33507](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33507)

Decodes a StatusPrivacyAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:33516](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33516)

Decodes a StatusPrivacyAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33489](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33489)

Encodes the specified StatusPrivacyAction message. Does not implicitly [verify](StatusPrivacyAction.md#verify) messages.

#### Parameters

##### message

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

StatusPrivacyAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33497](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33497)

Encodes the specified StatusPrivacyAction message, length delimited. Does not implicitly [verify](StatusPrivacyAction.md#verify) messages.

#### Parameters

##### message

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

StatusPrivacyAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:33530](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33530)

Creates a StatusPrivacyAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33538](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33538)

Creates a plain object from a StatusPrivacyAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33523](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33523)

Verifies a StatusPrivacyAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

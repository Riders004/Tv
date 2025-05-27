# Class: QuickReplyButton

Defined in: [WAProto/index.d.ts:35305](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35305)

Represents a QuickReplyButton.

## Implements

- [`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

## Constructors

### new QuickReplyButton()

> **new QuickReplyButton**(`properties`?): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:35311](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35311)

Constructs a new QuickReplyButton.

#### Parameters

##### properties?

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

Properties to set

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:35314](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35314)

QuickReplyButton displayText.

#### Implementation of

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md).[`displayText`](../interfaces/IQuickReplyButton.md#displaytext)

***

### id

> **id**: `string`

Defined in: [WAProto/index.d.ts:35317](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35317)

QuickReplyButton id.

#### Implementation of

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md).[`id`](../interfaces/IQuickReplyButton.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35387](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35387)

Converts this QuickReplyButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:35324](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35324)

Creates a new QuickReplyButton instance using the specified properties.

#### Parameters

##### properties?

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

Properties to set

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:35350](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35350)

Decodes a QuickReplyButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:35359](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35359)

Decodes a QuickReplyButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35332](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35332)

Encodes the specified QuickReplyButton message. Does not implicitly [verify](QuickReplyButton.md#verify) messages.

#### Parameters

##### message

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

QuickReplyButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35340](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35340)

Encodes the specified QuickReplyButton message, length delimited. Does not implicitly [verify](QuickReplyButton.md#verify) messages.

#### Parameters

##### message

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

QuickReplyButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:35373](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35373)

Creates a QuickReplyButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:35381](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35381)

Creates a plain object from a QuickReplyButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35366](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35366)

Verifies a QuickReplyButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

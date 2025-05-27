# Class: HydratedQuickReplyButton

Defined in: [WAProto/index.d.ts:7957](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7957)

Represents a HydratedQuickReplyButton.

## Implements

- [`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

## Constructors

### new HydratedQuickReplyButton()

> **new HydratedQuickReplyButton**(`properties`?): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:7963](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7963)

Constructs a new HydratedQuickReplyButton.

#### Parameters

##### properties?

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

Properties to set

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

## Properties

### displayText

> **displayText**: `string`

Defined in: [WAProto/index.d.ts:7966](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7966)

HydratedQuickReplyButton displayText.

#### Implementation of

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md).[`displayText`](../interfaces/IHydratedQuickReplyButton.md#displaytext)

***

### id

> **id**: `string`

Defined in: [WAProto/index.d.ts:7969](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7969)

HydratedQuickReplyButton id.

#### Implementation of

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md).[`id`](../interfaces/IHydratedQuickReplyButton.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8039](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8039)

Converts this HydratedQuickReplyButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:7976](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7976)

Creates a new HydratedQuickReplyButton instance using the specified properties.

#### Parameters

##### properties?

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

Properties to set

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:8002](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8002)

Decodes a HydratedQuickReplyButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:8011](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8011)

Decodes a HydratedQuickReplyButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7984](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7984)

Encodes the specified HydratedQuickReplyButton message. Does not implicitly [verify](HydratedQuickReplyButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

HydratedQuickReplyButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7992](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7992)

Encodes the specified HydratedQuickReplyButton message, length delimited. Does not implicitly [verify](HydratedQuickReplyButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

HydratedQuickReplyButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:8025](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8025)

Creates a HydratedQuickReplyButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8033](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8033)

Creates a plain object from a HydratedQuickReplyButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8018](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8018)

Verifies a HydratedQuickReplyButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

# Class: HydratedCallButton

Defined in: [WAProto/index.d.ts:7861](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7861)

Represents a HydratedCallButton.

## Implements

- [`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

## Constructors

### new HydratedCallButton()

> **new HydratedCallButton**(`properties`?): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:7867](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7867)

Constructs a new HydratedCallButton.

#### Parameters

##### properties?

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

Properties to set

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

## Properties

### displayText

> **displayText**: `string`

Defined in: [WAProto/index.d.ts:7870](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7870)

HydratedCallButton displayText.

#### Implementation of

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md).[`displayText`](../interfaces/IHydratedCallButton.md#displaytext)

***

### phoneNumber

> **phoneNumber**: `string`

Defined in: [WAProto/index.d.ts:7873](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7873)

HydratedCallButton phoneNumber.

#### Implementation of

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md).[`phoneNumber`](../interfaces/IHydratedCallButton.md#phonenumber)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7943](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7943)

Converts this HydratedCallButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:7880](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7880)

Creates a new HydratedCallButton instance using the specified properties.

#### Parameters

##### properties?

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

Properties to set

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:7906](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7906)

Decodes a HydratedCallButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:7915](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7915)

Decodes a HydratedCallButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7888](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7888)

Encodes the specified HydratedCallButton message. Does not implicitly [verify](HydratedCallButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

HydratedCallButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7896](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7896)

Encodes the specified HydratedCallButton message, length delimited. Does not implicitly [verify](HydratedCallButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

HydratedCallButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:7929](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7929)

Creates a HydratedCallButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:7937](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7937)

Creates a plain object from a HydratedCallButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7922](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L7922)

Verifies a HydratedCallButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

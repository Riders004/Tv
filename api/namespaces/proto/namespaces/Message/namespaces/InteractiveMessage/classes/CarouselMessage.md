# Class: CarouselMessage

Defined in: [WAProto/index.d.ts:15759](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15759)

Represents a CarouselMessage.

## Implements

- [`ICarouselMessage`](../interfaces/ICarouselMessage.md)

## Constructors

### new CarouselMessage()

> **new CarouselMessage**(`properties`?): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:15765](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15765)

Constructs a new CarouselMessage.

#### Parameters

##### properties?

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

Properties to set

#### Returns

[`CarouselMessage`](CarouselMessage.md)

## Properties

### cards

> **cards**: [`IInteractiveMessage`](../../../interfaces/IInteractiveMessage.md)[]

Defined in: [WAProto/index.d.ts:15768](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15768)

CarouselMessage cards.

#### Implementation of

[`ICarouselMessage`](../interfaces/ICarouselMessage.md).[`cards`](../interfaces/ICarouselMessage.md#cards)

***

### messageVersion

> **messageVersion**: `number`

Defined in: [WAProto/index.d.ts:15771](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15771)

CarouselMessage messageVersion.

#### Implementation of

[`ICarouselMessage`](../interfaces/ICarouselMessage.md).[`messageVersion`](../interfaces/ICarouselMessage.md#messageversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15841](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15841)

Converts this CarouselMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:15778](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15778)

Creates a new CarouselMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

Properties to set

#### Returns

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:15804](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15804)

Decodes a CarouselMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:15813](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15813)

Decodes a CarouselMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15786](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15786)

Encodes the specified CarouselMessage message. Does not implicitly [verify](CarouselMessage.md#verify) messages.

#### Parameters

##### message

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

CarouselMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15794](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15794)

Encodes the specified CarouselMessage message, length delimited. Does not implicitly [verify](CarouselMessage.md#verify) messages.

#### Parameters

##### message

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

CarouselMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:15827](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15827)

Creates a CarouselMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:15835](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15835)

Creates a plain object from a CarouselMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CarouselMessage`](CarouselMessage.md)

CarouselMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:15820](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L15820)

Verifies a CarouselMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

# Class: CtwaContextLinkData

Defined in: [WAProto/index.d.ts:2706](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2706)

Represents a CtwaContextLinkData.

## Implements

- [`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

## Constructors

### new CtwaContextLinkData()

> **new CtwaContextLinkData**(`properties`?): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2712](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2712)

Constructs a new CtwaContextLinkData.

#### Parameters

##### properties?

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

Properties to set

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

## Properties

### context

> **context**: `string`

Defined in: [WAProto/index.d.ts:2715](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2715)

CtwaContextLinkData context.

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`context`](../interfaces/ICtwaContextLinkData.md#context)

***

### icebreaker

> **icebreaker**: `string`

Defined in: [WAProto/index.d.ts:2721](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2721)

CtwaContextLinkData icebreaker.

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`icebreaker`](../interfaces/ICtwaContextLinkData.md#icebreaker)

***

### phone

> **phone**: `string`

Defined in: [WAProto/index.d.ts:2724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2724)

CtwaContextLinkData phone.

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`phone`](../interfaces/ICtwaContextLinkData.md#phone)

***

### sourceUrl

> **sourceUrl**: `string`

Defined in: [WAProto/index.d.ts:2718](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2718)

CtwaContextLinkData sourceUrl.

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`sourceUrl`](../interfaces/ICtwaContextLinkData.md#sourceurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2794](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2794)

Converts this CtwaContextLinkData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2731](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2731)

Creates a new CtwaContextLinkData instance using the specified properties.

#### Parameters

##### properties?

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

Properties to set

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2757](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2757)

Decodes a CtwaContextLinkData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2766](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2766)

Decodes a CtwaContextLinkData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2739](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2739)

Encodes the specified CtwaContextLinkData message. Does not implicitly [verify](CtwaContextLinkData.md#verify) messages.

#### Parameters

##### message

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

CtwaContextLinkData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2747](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2747)

Encodes the specified CtwaContextLinkData message, length delimited. Does not implicitly [verify](CtwaContextLinkData.md#verify) messages.

#### Parameters

##### message

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

CtwaContextLinkData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2780](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2780)

Creates a CtwaContextLinkData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:2788](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2788)

Creates a plain object from a CtwaContextLinkData message. Also converts values to other types if specified.

#### Parameters

##### message

[`CtwaContextLinkData`](CtwaContextLinkData.md)

CtwaContextLinkData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:2773](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2773)

Verifies a CtwaContextLinkData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

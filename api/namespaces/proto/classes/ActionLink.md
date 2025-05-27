# Class: ActionLink

Defined in: [WAProto/index.d.ts:562](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L562)

Represents an ActionLink.

## Implements

- [`IActionLink`](../interfaces/IActionLink.md)

## Constructors

### new ActionLink()

> **new ActionLink**(`properties`?): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:568](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L568)

Constructs a new ActionLink.

#### Parameters

##### properties?

[`IActionLink`](../interfaces/IActionLink.md)

Properties to set

#### Returns

[`ActionLink`](ActionLink.md)

## Properties

### buttonTitle

> **buttonTitle**: `string`

Defined in: [WAProto/index.d.ts:574](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L574)

ActionLink buttonTitle.

#### Implementation of

[`IActionLink`](../interfaces/IActionLink.md).[`buttonTitle`](../interfaces/IActionLink.md#buttontitle)

***

### url

> **url**: `string`

Defined in: [WAProto/index.d.ts:571](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L571)

ActionLink url.

#### Implementation of

[`IActionLink`](../interfaces/IActionLink.md).[`url`](../interfaces/IActionLink.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:644](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L644)

Converts this ActionLink to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:581](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L581)

Creates a new ActionLink instance using the specified properties.

#### Parameters

##### properties?

[`IActionLink`](../interfaces/IActionLink.md)

Properties to set

#### Returns

[`ActionLink`](ActionLink.md)

ActionLink instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:607](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L607)

Decodes an ActionLink message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ActionLink`](ActionLink.md)

ActionLink

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:616](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L616)

Decodes an ActionLink message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ActionLink`](ActionLink.md)

ActionLink

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:589](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L589)

Encodes the specified ActionLink message. Does not implicitly [verify](ActionLink.md#verify) messages.

#### Parameters

##### message

[`IActionLink`](../interfaces/IActionLink.md)

ActionLink message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:597](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L597)

Encodes the specified ActionLink message, length delimited. Does not implicitly [verify](ActionLink.md#verify) messages.

#### Parameters

##### message

[`IActionLink`](../interfaces/IActionLink.md)

ActionLink message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:630](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L630)

Creates an ActionLink message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ActionLink`](ActionLink.md)

ActionLink

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:638](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L638)

Creates a plain object from an ActionLink message. Also converts values to other types if specified.

#### Parameters

##### message

[`ActionLink`](ActionLink.md)

ActionLink

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:623](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L623)

Verifies an ActionLink message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

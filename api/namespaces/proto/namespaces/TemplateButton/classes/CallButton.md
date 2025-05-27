# Class: CallButton

Defined in: [WAProto/index.d.ts:35209](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35209)

Represents a CallButton.

## Implements

- [`ICallButton`](../interfaces/ICallButton.md)

## Constructors

### new CallButton()

> **new CallButton**(`properties`?): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:35215](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35215)

Constructs a new CallButton.

#### Parameters

##### properties?

[`ICallButton`](../interfaces/ICallButton.md)

Properties to set

#### Returns

[`CallButton`](CallButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:35218](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35218)

CallButton displayText.

#### Implementation of

[`ICallButton`](../interfaces/ICallButton.md).[`displayText`](../interfaces/ICallButton.md#displaytext)

***

### phoneNumber?

> `optional` **phoneNumber**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:35221](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35221)

CallButton phoneNumber.

#### Implementation of

[`ICallButton`](../interfaces/ICallButton.md).[`phoneNumber`](../interfaces/ICallButton.md#phonenumber)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35291](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35291)

Converts this CallButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:35228](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35228)

Creates a new CallButton instance using the specified properties.

#### Parameters

##### properties?

[`ICallButton`](../interfaces/ICallButton.md)

Properties to set

#### Returns

[`CallButton`](CallButton.md)

CallButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:35254](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35254)

Decodes a CallButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CallButton`](CallButton.md)

CallButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:35263](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35263)

Decodes a CallButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CallButton`](CallButton.md)

CallButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35236](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35236)

Encodes the specified CallButton message. Does not implicitly [verify](CallButton.md#verify) messages.

#### Parameters

##### message

[`ICallButton`](../interfaces/ICallButton.md)

CallButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35244](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35244)

Encodes the specified CallButton message, length delimited. Does not implicitly [verify](CallButton.md#verify) messages.

#### Parameters

##### message

[`ICallButton`](../interfaces/ICallButton.md)

CallButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:35277](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35277)

Creates a CallButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CallButton`](CallButton.md)

CallButton

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:35285](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35285)

Creates a plain object from a CallButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`CallButton`](CallButton.md)

CallButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35270](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L35270)

Verifies a CallButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

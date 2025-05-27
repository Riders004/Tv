# Class: CallLogAction

Defined in: [WAProto/index.d.ts:30235](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30235)

Represents a CallLogAction.

## Implements

- [`ICallLogAction`](../interfaces/ICallLogAction.md)

## Constructors

### new CallLogAction()

> **new CallLogAction**(`properties`?): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:30241](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30241)

Constructs a new CallLogAction.

#### Parameters

##### properties?

[`ICallLogAction`](../interfaces/ICallLogAction.md)

Properties to set

#### Returns

[`CallLogAction`](CallLogAction.md)

## Properties

### callLogRecord?

> `optional` **callLogRecord**: `null` \| [`ICallLogRecord`](../../../interfaces/ICallLogRecord.md)

Defined in: [WAProto/index.d.ts:30244](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30244)

CallLogAction callLogRecord.

#### Implementation of

[`ICallLogAction`](../interfaces/ICallLogAction.md).[`callLogRecord`](../interfaces/ICallLogAction.md#calllogrecord)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30314](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30314)

Converts this CallLogAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:30251](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30251)

Creates a new CallLogAction instance using the specified properties.

#### Parameters

##### properties?

[`ICallLogAction`](../interfaces/ICallLogAction.md)

Properties to set

#### Returns

[`CallLogAction`](CallLogAction.md)

CallLogAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:30277](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30277)

Decodes a CallLogAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CallLogAction`](CallLogAction.md)

CallLogAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:30286](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30286)

Decodes a CallLogAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CallLogAction`](CallLogAction.md)

CallLogAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30259](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30259)

Encodes the specified CallLogAction message. Does not implicitly [verify](CallLogAction.md#verify) messages.

#### Parameters

##### message

[`ICallLogAction`](../interfaces/ICallLogAction.md)

CallLogAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30267](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30267)

Encodes the specified CallLogAction message, length delimited. Does not implicitly [verify](CallLogAction.md#verify) messages.

#### Parameters

##### message

[`ICallLogAction`](../interfaces/ICallLogAction.md)

CallLogAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:30300](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30300)

Creates a CallLogAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CallLogAction`](CallLogAction.md)

CallLogAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:30308](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30308)

Creates a plain object from a CallLogAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`CallLogAction`](CallLogAction.md)

CallLogAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30293](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30293)

Verifies a CallLogAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

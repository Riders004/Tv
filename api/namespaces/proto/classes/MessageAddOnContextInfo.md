# Class: MessageAddOnContextInfo

Defined in: [WAProto/index.d.ts:23204](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23204)

Represents a MessageAddOnContextInfo.

## Implements

- [`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

## Constructors

### new MessageAddOnContextInfo()

> **new MessageAddOnContextInfo**(`properties`?): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:23210](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23210)

Constructs a new MessageAddOnContextInfo.

#### Parameters

##### properties?

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

Properties to set

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

## Properties

### messageAddOnDurationInSecs

> **messageAddOnDurationInSecs**: `number`

Defined in: [WAProto/index.d.ts:23213](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23213)

MessageAddOnContextInfo messageAddOnDurationInSecs.

#### Implementation of

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md).[`messageAddOnDurationInSecs`](../interfaces/IMessageAddOnContextInfo.md#messageaddondurationinsecs)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:23283](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23283)

Converts this MessageAddOnContextInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:23220](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23220)

Creates a new MessageAddOnContextInfo instance using the specified properties.

#### Parameters

##### properties?

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

Properties to set

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:23246](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23246)

Decodes a MessageAddOnContextInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:23255](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23255)

Decodes a MessageAddOnContextInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23228](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23228)

Encodes the specified MessageAddOnContextInfo message. Does not implicitly [verify](MessageAddOnContextInfo.md#verify) messages.

#### Parameters

##### message

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

MessageAddOnContextInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23236](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23236)

Encodes the specified MessageAddOnContextInfo message, length delimited. Does not implicitly [verify](MessageAddOnContextInfo.md#verify) messages.

#### Parameters

##### message

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

MessageAddOnContextInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:23269](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23269)

Creates a MessageAddOnContextInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:23277](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23277)

Creates a plain object from a MessageAddOnContextInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:23262](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23262)

Verifies a MessageAddOnContextInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

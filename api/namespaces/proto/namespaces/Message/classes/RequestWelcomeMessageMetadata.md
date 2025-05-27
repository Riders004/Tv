# Class: RequestWelcomeMessageMetadata

Defined in: [WAProto/index.d.ts:21629](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21629)

Represents a RequestWelcomeMessageMetadata.

## Implements

- [`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

## Constructors

### new RequestWelcomeMessageMetadata()

> **new RequestWelcomeMessageMetadata**(`properties`?): [`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:21635](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21635)

Constructs a new RequestWelcomeMessageMetadata.

#### Parameters

##### properties?

[`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

Properties to set

#### Returns

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

## Properties

### localChatState

> **localChatState**: [`LocalChatState`](../namespaces/RequestWelcomeMessageMetadata/enumerations/LocalChatState.md)

Defined in: [WAProto/index.d.ts:21638](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21638)

RequestWelcomeMessageMetadata localChatState.

#### Implementation of

[`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md).[`localChatState`](../interfaces/IRequestWelcomeMessageMetadata.md#localchatstate)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21708](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21708)

Converts this RequestWelcomeMessageMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:21645](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21645)

Creates a new RequestWelcomeMessageMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

Properties to set

#### Returns

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

RequestWelcomeMessageMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:21671](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21671)

Decodes a RequestWelcomeMessageMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

RequestWelcomeMessageMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:21680](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21680)

Decodes a RequestWelcomeMessageMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

RequestWelcomeMessageMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21653](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21653)

Encodes the specified RequestWelcomeMessageMetadata message. Does not implicitly [verify](RequestWelcomeMessageMetadata.md#verify) messages.

#### Parameters

##### message

[`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

RequestWelcomeMessageMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21661](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21661)

Encodes the specified RequestWelcomeMessageMetadata message, length delimited. Does not implicitly [verify](RequestWelcomeMessageMetadata.md#verify) messages.

#### Parameters

##### message

[`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

RequestWelcomeMessageMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:21694](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21694)

Creates a RequestWelcomeMessageMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

RequestWelcomeMessageMetadata

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:21702](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21702)

Creates a plain object from a RequestWelcomeMessageMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

RequestWelcomeMessageMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21687](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21687)

Verifies a RequestWelcomeMessageMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

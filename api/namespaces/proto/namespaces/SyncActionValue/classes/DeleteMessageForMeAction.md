# Class: DeleteMessageForMeAction

Defined in: [WAProto/index.d.ts:31186](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31186)

Represents a DeleteMessageForMeAction.

## Implements

- [`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md)

## Constructors

### new DeleteMessageForMeAction()

> **new DeleteMessageForMeAction**(`properties`?): [`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

Defined in: [WAProto/index.d.ts:31192](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31192)

Constructs a new DeleteMessageForMeAction.

#### Parameters

##### properties?

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md)

Properties to set

#### Returns

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

## Properties

### deleteMedia

> **deleteMedia**: `boolean`

Defined in: [WAProto/index.d.ts:31195](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31195)

DeleteMessageForMeAction deleteMedia.

#### Implementation of

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md).[`deleteMedia`](../interfaces/IDeleteMessageForMeAction.md#deletemedia)

***

### messageTimestamp

> **messageTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:31198](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31198)

DeleteMessageForMeAction messageTimestamp.

#### Implementation of

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md).[`messageTimestamp`](../interfaces/IDeleteMessageForMeAction.md#messagetimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31268](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31268)

Converts this DeleteMessageForMeAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

Defined in: [WAProto/index.d.ts:31205](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31205)

Creates a new DeleteMessageForMeAction instance using the specified properties.

#### Parameters

##### properties?

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md)

Properties to set

#### Returns

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

DeleteMessageForMeAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

Defined in: [WAProto/index.d.ts:31231](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31231)

Decodes a DeleteMessageForMeAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

DeleteMessageForMeAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

Defined in: [WAProto/index.d.ts:31240](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31240)

Decodes a DeleteMessageForMeAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

DeleteMessageForMeAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31213](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31213)

Encodes the specified DeleteMessageForMeAction message. Does not implicitly [verify](DeleteMessageForMeAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md)

DeleteMessageForMeAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31221](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31221)

Encodes the specified DeleteMessageForMeAction message, length delimited. Does not implicitly [verify](DeleteMessageForMeAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md)

DeleteMessageForMeAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

Defined in: [WAProto/index.d.ts:31254](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31254)

Creates a DeleteMessageForMeAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

DeleteMessageForMeAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:31262](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31262)

Creates a plain object from a DeleteMessageForMeAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

DeleteMessageForMeAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31247](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31247)

Verifies a DeleteMessageForMeAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

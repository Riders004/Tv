# Class: AppStateFatalExceptionNotification

Defined in: [WAProto/index.d.ts:10113](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10113)

Represents an AppStateFatalExceptionNotification.

## Implements

- [`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

## Constructors

### new AppStateFatalExceptionNotification()

> **new AppStateFatalExceptionNotification**(`properties`?): [`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:10119](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10119)

Constructs a new AppStateFatalExceptionNotification.

#### Parameters

##### properties?

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

Properties to set

#### Returns

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

## Properties

### collectionNames

> **collectionNames**: `string`[]

Defined in: [WAProto/index.d.ts:10122](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10122)

AppStateFatalExceptionNotification collectionNames.

#### Implementation of

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md).[`collectionNames`](../interfaces/IAppStateFatalExceptionNotification.md#collectionnames)

***

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:10125](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10125)

AppStateFatalExceptionNotification timestamp.

#### Implementation of

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md).[`timestamp`](../interfaces/IAppStateFatalExceptionNotification.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10195](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10195)

Converts this AppStateFatalExceptionNotification to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:10132](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10132)

Creates a new AppStateFatalExceptionNotification instance using the specified properties.

#### Parameters

##### properties?

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

Properties to set

#### Returns

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

AppStateFatalExceptionNotification instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:10158](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10158)

Decodes an AppStateFatalExceptionNotification message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

AppStateFatalExceptionNotification

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:10167](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10167)

Decodes an AppStateFatalExceptionNotification message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

AppStateFatalExceptionNotification

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10140](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10140)

Encodes the specified AppStateFatalExceptionNotification message. Does not implicitly [verify](AppStateFatalExceptionNotification.md#verify) messages.

#### Parameters

##### message

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

AppStateFatalExceptionNotification message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10148](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10148)

Encodes the specified AppStateFatalExceptionNotification message, length delimited. Does not implicitly [verify](AppStateFatalExceptionNotification.md#verify) messages.

#### Parameters

##### message

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

AppStateFatalExceptionNotification message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:10181](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10181)

Creates an AppStateFatalExceptionNotification message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

AppStateFatalExceptionNotification

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:10189](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10189)

Creates a plain object from an AppStateFatalExceptionNotification message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

AppStateFatalExceptionNotification

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10174](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10174)

Verifies an AppStateFatalExceptionNotification message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

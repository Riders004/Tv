# Class: AppStateSyncKeyFingerprint

Defined in: [WAProto/index.d.ts:10410](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10410)

Represents an AppStateSyncKeyFingerprint.

## Implements

- [`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

## Constructors

### new AppStateSyncKeyFingerprint()

> **new AppStateSyncKeyFingerprint**(`properties`?): [`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:10416](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10416)

Constructs a new AppStateSyncKeyFingerprint.

#### Parameters

##### properties?

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

Properties to set

#### Returns

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

## Properties

### currentIndex

> **currentIndex**: `number`

Defined in: [WAProto/index.d.ts:10422](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10422)

AppStateSyncKeyFingerprint currentIndex.

#### Implementation of

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md).[`currentIndex`](../interfaces/IAppStateSyncKeyFingerprint.md#currentindex)

***

### deviceIndexes

> **deviceIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:10425](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10425)

AppStateSyncKeyFingerprint deviceIndexes.

#### Implementation of

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md).[`deviceIndexes`](../interfaces/IAppStateSyncKeyFingerprint.md#deviceindexes)

***

### rawId

> **rawId**: `number`

Defined in: [WAProto/index.d.ts:10419](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10419)

AppStateSyncKeyFingerprint rawId.

#### Implementation of

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md).[`rawId`](../interfaces/IAppStateSyncKeyFingerprint.md#rawid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10495](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10495)

Converts this AppStateSyncKeyFingerprint to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:10432](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10432)

Creates a new AppStateSyncKeyFingerprint instance using the specified properties.

#### Parameters

##### properties?

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

Properties to set

#### Returns

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

AppStateSyncKeyFingerprint instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:10458](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10458)

Decodes an AppStateSyncKeyFingerprint message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

AppStateSyncKeyFingerprint

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:10467](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10467)

Decodes an AppStateSyncKeyFingerprint message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

AppStateSyncKeyFingerprint

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10440](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10440)

Encodes the specified AppStateSyncKeyFingerprint message. Does not implicitly [verify](AppStateSyncKeyFingerprint.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

AppStateSyncKeyFingerprint message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10448](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10448)

Encodes the specified AppStateSyncKeyFingerprint message, length delimited. Does not implicitly [verify](AppStateSyncKeyFingerprint.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

AppStateSyncKeyFingerprint message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:10481](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10481)

Creates an AppStateSyncKeyFingerprint message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

AppStateSyncKeyFingerprint

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:10489](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10489)

Creates a plain object from an AppStateSyncKeyFingerprint message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

AppStateSyncKeyFingerprint

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10474](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10474)

Verifies an AppStateSyncKeyFingerprint message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

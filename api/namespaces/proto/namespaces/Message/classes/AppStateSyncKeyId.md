# Class: AppStateSyncKeyId

Defined in: [WAProto/index.d.ts:10506](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10506)

Represents an AppStateSyncKeyId.

## Implements

- [`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

## Constructors

### new AppStateSyncKeyId()

> **new AppStateSyncKeyId**(`properties`?): [`AppStateSyncKeyId`](AppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:10512](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10512)

Constructs a new AppStateSyncKeyId.

#### Parameters

##### properties?

[`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

Properties to set

#### Returns

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

## Properties

### keyId

> **keyId**: `Uint8Array`

Defined in: [WAProto/index.d.ts:10515](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10515)

AppStateSyncKeyId keyId.

#### Implementation of

[`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md).[`keyId`](../interfaces/IAppStateSyncKeyId.md#keyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10585](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10585)

Converts this AppStateSyncKeyId to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyId`](AppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:10522](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10522)

Creates a new AppStateSyncKeyId instance using the specified properties.

#### Parameters

##### properties?

[`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

Properties to set

#### Returns

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

AppStateSyncKeyId instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppStateSyncKeyId`](AppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:10548](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10548)

Decodes an AppStateSyncKeyId message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

AppStateSyncKeyId

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppStateSyncKeyId`](AppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:10557](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10557)

Decodes an AppStateSyncKeyId message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

AppStateSyncKeyId

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10530](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10530)

Encodes the specified AppStateSyncKeyId message. Does not implicitly [verify](AppStateSyncKeyId.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

AppStateSyncKeyId message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10538](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10538)

Encodes the specified AppStateSyncKeyId message, length delimited. Does not implicitly [verify](AppStateSyncKeyId.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

AppStateSyncKeyId message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppStateSyncKeyId`](AppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:10571](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10571)

Creates an AppStateSyncKeyId message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

AppStateSyncKeyId

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:10579](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10579)

Creates a plain object from an AppStateSyncKeyId message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

AppStateSyncKeyId

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10564](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10564)

Verifies an AppStateSyncKeyId message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

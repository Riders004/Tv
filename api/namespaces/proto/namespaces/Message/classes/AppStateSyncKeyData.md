# Class: AppStateSyncKeyData

Defined in: [WAProto/index.d.ts:10308](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10308)

Represents an AppStateSyncKeyData.

## Implements

- [`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

## Constructors

### new AppStateSyncKeyData()

> **new AppStateSyncKeyData**(`properties`?): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:10314](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10314)

Constructs a new AppStateSyncKeyData.

#### Parameters

##### properties?

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

Properties to set

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

## Properties

### fingerprint?

> `optional` **fingerprint**: `null` \| [`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:10320](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10320)

AppStateSyncKeyData fingerprint.

#### Implementation of

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md).[`fingerprint`](../interfaces/IAppStateSyncKeyData.md#fingerprint)

***

### keyData

> **keyData**: `Uint8Array`

Defined in: [WAProto/index.d.ts:10317](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10317)

AppStateSyncKeyData keyData.

#### Implementation of

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md).[`keyData`](../interfaces/IAppStateSyncKeyData.md#keydata)

***

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:10323](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10323)

AppStateSyncKeyData timestamp.

#### Implementation of

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md).[`timestamp`](../interfaces/IAppStateSyncKeyData.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10393](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10393)

Converts this AppStateSyncKeyData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:10330](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10330)

Creates a new AppStateSyncKeyData instance using the specified properties.

#### Parameters

##### properties?

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

Properties to set

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:10356](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10356)

Decodes an AppStateSyncKeyData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:10365](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10365)

Decodes an AppStateSyncKeyData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10338](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10338)

Encodes the specified AppStateSyncKeyData message. Does not implicitly [verify](AppStateSyncKeyData.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

AppStateSyncKeyData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10346](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10346)

Encodes the specified AppStateSyncKeyData message, length delimited. Does not implicitly [verify](AppStateSyncKeyData.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

AppStateSyncKeyData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:10379](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10379)

Creates an AppStateSyncKeyData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:10387](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10387)

Creates a plain object from an AppStateSyncKeyData message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10372](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10372)

Verifies an AppStateSyncKeyData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

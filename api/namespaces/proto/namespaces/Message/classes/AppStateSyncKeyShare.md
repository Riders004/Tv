# Class: AppStateSyncKeyShare

Defined in: [WAProto/index.d.ts:10686](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10686)

Represents an AppStateSyncKeyShare.

## Implements

- [`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

## Constructors

### new AppStateSyncKeyShare()

> **new AppStateSyncKeyShare**(`properties`?): [`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:10692](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10692)

Constructs a new AppStateSyncKeyShare.

#### Parameters

##### properties?

[`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

Properties to set

#### Returns

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

## Properties

### keys

> **keys**: [`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)[]

Defined in: [WAProto/index.d.ts:10695](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10695)

AppStateSyncKeyShare keys.

#### Implementation of

[`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md).[`keys`](../interfaces/IAppStateSyncKeyShare.md#keys)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10765](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10765)

Converts this AppStateSyncKeyShare to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:10702](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10702)

Creates a new AppStateSyncKeyShare instance using the specified properties.

#### Parameters

##### properties?

[`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

Properties to set

#### Returns

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

AppStateSyncKeyShare instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:10728](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10728)

Decodes an AppStateSyncKeyShare message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

AppStateSyncKeyShare

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:10737](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10737)

Decodes an AppStateSyncKeyShare message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

AppStateSyncKeyShare

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10710](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10710)

Encodes the specified AppStateSyncKeyShare message. Does not implicitly [verify](AppStateSyncKeyShare.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

AppStateSyncKeyShare message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10718](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10718)

Encodes the specified AppStateSyncKeyShare message, length delimited. Does not implicitly [verify](AppStateSyncKeyShare.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

AppStateSyncKeyShare message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:10751](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10751)

Creates an AppStateSyncKeyShare message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

AppStateSyncKeyShare

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:10759](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10759)

Creates a plain object from an AppStateSyncKeyShare message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

AppStateSyncKeyShare

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10744](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10744)

Verifies an AppStateSyncKeyShare message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

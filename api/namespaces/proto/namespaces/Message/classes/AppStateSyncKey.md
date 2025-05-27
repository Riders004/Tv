# Class: AppStateSyncKey

Defined in: [WAProto/index.d.ts:10209](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10209)

Represents an AppStateSyncKey.

## Implements

- [`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)

## Constructors

### new AppStateSyncKey()

> **new AppStateSyncKey**(`properties`?): [`AppStateSyncKey`](AppStateSyncKey.md)

Defined in: [WAProto/index.d.ts:10215](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10215)

Constructs a new AppStateSyncKey.

#### Parameters

##### properties?

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)

Properties to set

#### Returns

[`AppStateSyncKey`](AppStateSyncKey.md)

## Properties

### keyData?

> `optional` **keyData**: `null` \| [`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:10221](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10221)

AppStateSyncKey keyData.

#### Implementation of

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md).[`keyData`](../interfaces/IAppStateSyncKey.md#keydata)

***

### keyId?

> `optional` **keyId**: `null` \| [`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:10218](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10218)

AppStateSyncKey keyId.

#### Implementation of

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md).[`keyId`](../interfaces/IAppStateSyncKey.md#keyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10291](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10291)

Converts this AppStateSyncKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKey`](AppStateSyncKey.md)

Defined in: [WAProto/index.d.ts:10228](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10228)

Creates a new AppStateSyncKey instance using the specified properties.

#### Parameters

##### properties?

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)

Properties to set

#### Returns

[`AppStateSyncKey`](AppStateSyncKey.md)

AppStateSyncKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppStateSyncKey`](AppStateSyncKey.md)

Defined in: [WAProto/index.d.ts:10254](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10254)

Decodes an AppStateSyncKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppStateSyncKey`](AppStateSyncKey.md)

AppStateSyncKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppStateSyncKey`](AppStateSyncKey.md)

Defined in: [WAProto/index.d.ts:10263](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10263)

Decodes an AppStateSyncKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppStateSyncKey`](AppStateSyncKey.md)

AppStateSyncKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10236](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10236)

Encodes the specified AppStateSyncKey message. Does not implicitly [verify](AppStateSyncKey.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)

AppStateSyncKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10244](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10244)

Encodes the specified AppStateSyncKey message, length delimited. Does not implicitly [verify](AppStateSyncKey.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)

AppStateSyncKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppStateSyncKey`](AppStateSyncKey.md)

Defined in: [WAProto/index.d.ts:10277](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10277)

Creates an AppStateSyncKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppStateSyncKey`](AppStateSyncKey.md)

AppStateSyncKey

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:10285](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10285)

Creates a plain object from an AppStateSyncKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppStateSyncKey`](AppStateSyncKey.md)

AppStateSyncKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10270](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10270)

Verifies an AppStateSyncKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

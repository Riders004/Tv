# Class: AppStateSyncKeyRequest

Defined in: [WAProto/index.d.ts:10596](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10596)

Represents an AppStateSyncKeyRequest.

## Implements

- [`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

## Constructors

### new AppStateSyncKeyRequest()

> **new AppStateSyncKeyRequest**(`properties`?): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:10602](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10602)

Constructs a new AppStateSyncKeyRequest.

#### Parameters

##### properties?

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

Properties to set

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

## Properties

### keyIds

> **keyIds**: [`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)[]

Defined in: [WAProto/index.d.ts:10605](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10605)

AppStateSyncKeyRequest keyIds.

#### Implementation of

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md).[`keyIds`](../interfaces/IAppStateSyncKeyRequest.md#keyids)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10675](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10675)

Converts this AppStateSyncKeyRequest to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:10612](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10612)

Creates a new AppStateSyncKeyRequest instance using the specified properties.

#### Parameters

##### properties?

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

Properties to set

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:10638](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10638)

Decodes an AppStateSyncKeyRequest message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:10647](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10647)

Decodes an AppStateSyncKeyRequest message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10620](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10620)

Encodes the specified AppStateSyncKeyRequest message. Does not implicitly [verify](AppStateSyncKeyRequest.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

AppStateSyncKeyRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10628](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10628)

Encodes the specified AppStateSyncKeyRequest message, length delimited. Does not implicitly [verify](AppStateSyncKeyRequest.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

AppStateSyncKeyRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:10661](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10661)

Creates an AppStateSyncKeyRequest message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:10669](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10669)

Creates a plain object from an AppStateSyncKeyRequest message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10654](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L10654)

Verifies an AppStateSyncKeyRequest message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

# Class: DNSSource

Defined in: [WAProto/index.d.ts:3088](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3088)

Represents a DNSSource.

## Implements

- [`IDNSSource`](../interfaces/IDNSSource.md)

## Constructors

### new DNSSource()

> **new DNSSource**(`properties`?): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:3094](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3094)

Constructs a new DNSSource.

#### Parameters

##### properties?

[`IDNSSource`](../interfaces/IDNSSource.md)

Properties to set

#### Returns

[`DNSSource`](DNSSource.md)

## Properties

### appCached

> **appCached**: `boolean`

Defined in: [WAProto/index.d.ts:3100](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3100)

DNSSource appCached.

#### Implementation of

[`IDNSSource`](../interfaces/IDNSSource.md).[`appCached`](../interfaces/IDNSSource.md#appcached)

***

### dnsMethod

> **dnsMethod**: [`DNSResolutionMethod`](../namespaces/DNSSource/enumerations/DNSResolutionMethod.md)

Defined in: [WAProto/index.d.ts:3097](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3097)

DNSSource dnsMethod.

#### Implementation of

[`IDNSSource`](../interfaces/IDNSSource.md).[`dnsMethod`](../interfaces/IDNSSource.md#dnsmethod)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3170](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3170)

Converts this DNSSource to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:3107](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3107)

Creates a new DNSSource instance using the specified properties.

#### Parameters

##### properties?

[`IDNSSource`](../interfaces/IDNSSource.md)

Properties to set

#### Returns

[`DNSSource`](DNSSource.md)

DNSSource instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:3133](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3133)

Decodes a DNSSource message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DNSSource`](DNSSource.md)

DNSSource

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:3142](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3142)

Decodes a DNSSource message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DNSSource`](DNSSource.md)

DNSSource

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3115](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3115)

Encodes the specified DNSSource message. Does not implicitly [verify](DNSSource.md#verify) messages.

#### Parameters

##### message

[`IDNSSource`](../interfaces/IDNSSource.md)

DNSSource message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3123](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3123)

Encodes the specified DNSSource message, length delimited. Does not implicitly [verify](DNSSource.md#verify) messages.

#### Parameters

##### message

[`IDNSSource`](../interfaces/IDNSSource.md)

DNSSource message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:3156](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3156)

Creates a DNSSource message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DNSSource`](DNSSource.md)

DNSSource

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:3164](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3164)

Creates a plain object from a DNSSource message. Also converts values to other types if specified.

#### Parameters

##### message

[`DNSSource`](DNSSource.md)

DNSSource

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3149](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3149)

Verifies a DNSSource message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

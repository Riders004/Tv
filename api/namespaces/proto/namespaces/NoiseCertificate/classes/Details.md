# Class: Details

Defined in: [WAProto/index.d.ts:24301](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24301)

Represents a Details.

## Implements

- [`IDetails`](../interfaces/IDetails.md)

## Constructors

### new Details()

> **new Details**(`properties`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:24307](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24307)

Constructs a new Details.

#### Parameters

##### properties?

[`IDetails`](../interfaces/IDetails.md)

Properties to set

#### Returns

[`Details`](Details.md)

## Properties

### expires

> **expires**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:24316](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24316)

Details expires.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`expires`](../interfaces/IDetails.md#expires)

***

### issuer

> **issuer**: `string`

Defined in: [WAProto/index.d.ts:24313](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24313)

Details issuer.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`issuer`](../interfaces/IDetails.md#issuer)

***

### key

> **key**: `Uint8Array`

Defined in: [WAProto/index.d.ts:24322](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24322)

Details key.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`key`](../interfaces/IDetails.md#key)

***

### serial

> **serial**: `number`

Defined in: [WAProto/index.d.ts:24310](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24310)

Details serial.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`serial`](../interfaces/IDetails.md#serial)

***

### subject

> **subject**: `string`

Defined in: [WAProto/index.d.ts:24319](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24319)

Details subject.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`subject`](../interfaces/IDetails.md#subject)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:24392](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24392)

Converts this Details to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:24329](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24329)

Creates a new Details instance using the specified properties.

#### Parameters

##### properties?

[`IDetails`](../interfaces/IDetails.md)

Properties to set

#### Returns

[`Details`](Details.md)

Details instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:24355](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24355)

Decodes a Details message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Details`](Details.md)

Details

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:24364](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24364)

Decodes a Details message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Details`](Details.md)

Details

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24337](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24337)

Encodes the specified Details message. Does not implicitly [verify](Details.md#verify) messages.

#### Parameters

##### message

[`IDetails`](../interfaces/IDetails.md)

Details message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24345](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24345)

Encodes the specified Details message, length delimited. Does not implicitly [verify](Details.md#verify) messages.

#### Parameters

##### message

[`IDetails`](../interfaces/IDetails.md)

Details message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:24378](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24378)

Creates a Details message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Details`](Details.md)

Details

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:24386](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24386)

Creates a plain object from a Details message. Also converts values to other types if specified.

#### Parameters

##### message

[`Details`](Details.md)

Details

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:24371](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L24371)

Verifies a Details message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

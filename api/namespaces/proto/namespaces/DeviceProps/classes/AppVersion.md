# Class: AppVersion

Defined in: [WAProto/index.d.ts:5852](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5852)

Represents an AppVersion.

## Implements

- [`IAppVersion`](../interfaces/IAppVersion.md)

## Constructors

### new AppVersion()

> **new AppVersion**(`properties`?): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:5858](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5858)

Constructs a new AppVersion.

#### Parameters

##### properties?

[`IAppVersion`](../interfaces/IAppVersion.md)

Properties to set

#### Returns

[`AppVersion`](AppVersion.md)

## Properties

### primary

> **primary**: `number`

Defined in: [WAProto/index.d.ts:5861](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5861)

AppVersion primary.

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`primary`](../interfaces/IAppVersion.md#primary)

***

### quaternary

> **quaternary**: `number`

Defined in: [WAProto/index.d.ts:5870](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5870)

AppVersion quaternary.

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`quaternary`](../interfaces/IAppVersion.md#quaternary)

***

### quinary

> **quinary**: `number`

Defined in: [WAProto/index.d.ts:5873](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5873)

AppVersion quinary.

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`quinary`](../interfaces/IAppVersion.md#quinary)

***

### secondary

> **secondary**: `number`

Defined in: [WAProto/index.d.ts:5864](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5864)

AppVersion secondary.

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`secondary`](../interfaces/IAppVersion.md#secondary)

***

### tertiary

> **tertiary**: `number`

Defined in: [WAProto/index.d.ts:5867](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5867)

AppVersion tertiary.

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`tertiary`](../interfaces/IAppVersion.md#tertiary)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5943](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5943)

Converts this AppVersion to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:5880](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5880)

Creates a new AppVersion instance using the specified properties.

#### Parameters

##### properties?

[`IAppVersion`](../interfaces/IAppVersion.md)

Properties to set

#### Returns

[`AppVersion`](AppVersion.md)

AppVersion instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:5906](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5906)

Decodes an AppVersion message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppVersion`](AppVersion.md)

AppVersion

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:5915](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5915)

Decodes an AppVersion message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppVersion`](AppVersion.md)

AppVersion

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5888](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5888)

Encodes the specified AppVersion message. Does not implicitly [verify](AppVersion.md#verify) messages.

#### Parameters

##### message

[`IAppVersion`](../interfaces/IAppVersion.md)

AppVersion message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5896](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5896)

Encodes the specified AppVersion message, length delimited. Does not implicitly [verify](AppVersion.md#verify) messages.

#### Parameters

##### message

[`IAppVersion`](../interfaces/IAppVersion.md)

AppVersion message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:5929](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5929)

Creates an AppVersion message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppVersion`](AppVersion.md)

AppVersion

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:5937](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5937)

Creates a plain object from an AppVersion message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppVersion`](AppVersion.md)

AppVersion

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5922](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L5922)

Verifies an AppVersion message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

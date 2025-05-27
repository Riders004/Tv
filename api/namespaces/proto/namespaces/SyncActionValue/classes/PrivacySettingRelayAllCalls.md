# Class: PrivacySettingRelayAllCalls

Defined in: [WAProto/index.d.ts:32805](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32805)

Represents a PrivacySettingRelayAllCalls.

## Implements

- [`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

## Constructors

### new PrivacySettingRelayAllCalls()

> **new PrivacySettingRelayAllCalls**(`properties`?): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:32811](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32811)

Constructs a new PrivacySettingRelayAllCalls.

#### Parameters

##### properties?

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

Properties to set

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

## Properties

### isEnabled

> **isEnabled**: `boolean`

Defined in: [WAProto/index.d.ts:32814](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32814)

PrivacySettingRelayAllCalls isEnabled.

#### Implementation of

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md).[`isEnabled`](../interfaces/IPrivacySettingRelayAllCalls.md#isenabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32884](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32884)

Converts this PrivacySettingRelayAllCalls to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:32821](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32821)

Creates a new PrivacySettingRelayAllCalls instance using the specified properties.

#### Parameters

##### properties?

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

Properties to set

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:32847](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32847)

Decodes a PrivacySettingRelayAllCalls message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:32856](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32856)

Decodes a PrivacySettingRelayAllCalls message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32829](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32829)

Encodes the specified PrivacySettingRelayAllCalls message. Does not implicitly [verify](PrivacySettingRelayAllCalls.md#verify) messages.

#### Parameters

##### message

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32837](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32837)

Encodes the specified PrivacySettingRelayAllCalls message, length delimited. Does not implicitly [verify](PrivacySettingRelayAllCalls.md#verify) messages.

#### Parameters

##### message

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:32870](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32870)

Creates a PrivacySettingRelayAllCalls message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:32878](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32878)

Creates a plain object from a PrivacySettingRelayAllCalls message. Also converts values to other types if specified.

#### Parameters

##### message

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32863](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L32863)

Verifies a PrivacySettingRelayAllCalls message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

# Class: BizIdentityInfo

Defined in: [WAProto/index.d.ts:1104](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1104)

Represents a BizIdentityInfo.

## Implements

- [`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

## Constructors

### new BizIdentityInfo()

> **new BizIdentityInfo**(`properties`?): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:1110](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1110)

Constructs a new BizIdentityInfo.

#### Parameters

##### properties?

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

Properties to set

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

## Properties

### actualActors

> **actualActors**: [`ActualActorsType`](../namespaces/BizIdentityInfo/enumerations/ActualActorsType.md)

Defined in: [WAProto/index.d.ts:1128](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1128)

BizIdentityInfo actualActors.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`actualActors`](../interfaces/IBizIdentityInfo.md#actualactors)

***

### featureControls

> **featureControls**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:1134](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1134)

BizIdentityInfo featureControls.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`featureControls`](../interfaces/IBizIdentityInfo.md#featurecontrols)

***

### hostStorage

> **hostStorage**: [`HostStorageType`](../namespaces/BizIdentityInfo/enumerations/HostStorageType.md)

Defined in: [WAProto/index.d.ts:1125](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1125)

BizIdentityInfo hostStorage.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`hostStorage`](../interfaces/IBizIdentityInfo.md#hoststorage)

***

### privacyModeTs

> **privacyModeTs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:1131](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1131)

BizIdentityInfo privacyModeTs.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`privacyModeTs`](../interfaces/IBizIdentityInfo.md#privacymodets)

***

### revoked

> **revoked**: `boolean`

Defined in: [WAProto/index.d.ts:1122](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1122)

BizIdentityInfo revoked.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`revoked`](../interfaces/IBizIdentityInfo.md#revoked)

***

### signed

> **signed**: `boolean`

Defined in: [WAProto/index.d.ts:1119](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1119)

BizIdentityInfo signed.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`signed`](../interfaces/IBizIdentityInfo.md#signed)

***

### vlevel

> **vlevel**: [`VerifiedLevelValue`](../namespaces/BizIdentityInfo/enumerations/VerifiedLevelValue.md)

Defined in: [WAProto/index.d.ts:1113](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1113)

BizIdentityInfo vlevel.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`vlevel`](../interfaces/IBizIdentityInfo.md#vlevel)

***

### vnameCert?

> `optional` **vnameCert**: `null` \| [`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:1116](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1116)

BizIdentityInfo vnameCert.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`vnameCert`](../interfaces/IBizIdentityInfo.md#vnamecert)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1204](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1204)

Converts this BizIdentityInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:1141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1141)

Creates a new BizIdentityInfo instance using the specified properties.

#### Parameters

##### properties?

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

Properties to set

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:1167](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1167)

Decodes a BizIdentityInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:1176](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1176)

Decodes a BizIdentityInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1149](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1149)

Encodes the specified BizIdentityInfo message. Does not implicitly [verify](BizIdentityInfo.md#verify) messages.

#### Parameters

##### message

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

BizIdentityInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1157](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1157)

Encodes the specified BizIdentityInfo message, length delimited. Does not implicitly [verify](BizIdentityInfo.md#verify) messages.

#### Parameters

##### message

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

BizIdentityInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:1190](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1190)

Creates a BizIdentityInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:1198](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1198)

Creates a plain object from a BizIdentityInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1183](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L1183)

Verifies a BizIdentityInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

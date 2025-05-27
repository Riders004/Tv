# Class: BizAccountLinkInfo

Defined in: [WAProto/index.d.ts:871](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L871)

Represents a BizAccountLinkInfo.

## Implements

- [`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

## Constructors

### new BizAccountLinkInfo()

> **new BizAccountLinkInfo**(`properties`?): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:877](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L877)

Constructs a new BizAccountLinkInfo.

#### Parameters

##### properties?

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

Properties to set

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

## Properties

### accountType

> **accountType**: [`ENTERPRISE`](../namespaces/BizAccountLinkInfo/enumerations/AccountType.md#enterprise)

Defined in: [WAProto/index.d.ts:892](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L892)

BizAccountLinkInfo accountType.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`accountType`](../interfaces/IBizAccountLinkInfo.md#accounttype)

***

### hostStorage

> **hostStorage**: [`HostStorageType`](../namespaces/BizAccountLinkInfo/enumerations/HostStorageType.md)

Defined in: [WAProto/index.d.ts:889](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L889)

BizAccountLinkInfo hostStorage.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`hostStorage`](../interfaces/IBizAccountLinkInfo.md#hoststorage)

***

### issueTime

> **issueTime**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:886](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L886)

BizAccountLinkInfo issueTime.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`issueTime`](../interfaces/IBizAccountLinkInfo.md#issuetime)

***

### whatsappAcctNumber

> **whatsappAcctNumber**: `string`

Defined in: [WAProto/index.d.ts:883](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L883)

BizAccountLinkInfo whatsappAcctNumber.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`whatsappAcctNumber`](../interfaces/IBizAccountLinkInfo.md#whatsappacctnumber)

***

### whatsappBizAcctFbid

> **whatsappBizAcctFbid**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:880](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L880)

BizAccountLinkInfo whatsappBizAcctFbid.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`whatsappBizAcctFbid`](../interfaces/IBizAccountLinkInfo.md#whatsappbizacctfbid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:962](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L962)

Converts this BizAccountLinkInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:899](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L899)

Creates a new BizAccountLinkInfo instance using the specified properties.

#### Parameters

##### properties?

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

Properties to set

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:925](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L925)

Decodes a BizAccountLinkInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:934](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L934)

Decodes a BizAccountLinkInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:907](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L907)

Encodes the specified BizAccountLinkInfo message. Does not implicitly [verify](BizAccountLinkInfo.md#verify) messages.

#### Parameters

##### message

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

BizAccountLinkInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:915](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L915)

Encodes the specified BizAccountLinkInfo message, length delimited. Does not implicitly [verify](BizAccountLinkInfo.md#verify) messages.

#### Parameters

##### message

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

BizAccountLinkInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:948](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L948)

Creates a BizAccountLinkInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:956](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L956)

Creates a plain object from a BizAccountLinkInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:941](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L941)

Verifies a BizAccountLinkInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

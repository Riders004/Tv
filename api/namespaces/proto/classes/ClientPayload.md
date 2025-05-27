# Class: ClientPayload

Defined in: [WAProto/index.d.ts:2885](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2885)

Represents a ClientPayload.

## Implements

- [`IClientPayload`](../interfaces/IClientPayload.md)

## Constructors

### new ClientPayload()

> **new ClientPayload**(`properties`?): [`ClientPayload`](ClientPayload.md)

Defined in: [WAProto/index.d.ts:2891](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2891)

Constructs a new ClientPayload.

#### Parameters

##### properties?

[`IClientPayload`](../interfaces/IClientPayload.md)

Properties to set

#### Returns

[`ClientPayload`](ClientPayload.md)

## Properties

### connectAttemptCount

> **connectAttemptCount**: `number`

Defined in: [WAProto/index.d.ts:2927](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2927)

ClientPayload connectAttemptCount.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`connectAttemptCount`](../interfaces/IClientPayload.md#connectattemptcount)

***

### connectReason

> **connectReason**: [`ConnectReason`](../namespaces/ClientPayload/enumerations/ConnectReason.md)

Defined in: [WAProto/index.d.ts:2918](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2918)

ClientPayload connectReason.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`connectReason`](../interfaces/IClientPayload.md#connectreason)

***

### connectType

> **connectType**: [`ConnectType`](../namespaces/ClientPayload/enumerations/ConnectType.md)

Defined in: [WAProto/index.d.ts:2915](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2915)

ClientPayload connectType.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`connectType`](../interfaces/IClientPayload.md#connecttype)

***

### device

> **device**: `number`

Defined in: [WAProto/index.d.ts:2930](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2930)

ClientPayload device.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`device`](../interfaces/IClientPayload.md#device)

***

### devicePairingData?

> `optional` **devicePairingData**: `null` \| [`IDevicePairingRegistrationData`](../namespaces/ClientPayload/interfaces/IDevicePairingRegistrationData.md)

Defined in: [WAProto/index.d.ts:2933](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2933)

ClientPayload devicePairingData.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`devicePairingData`](../interfaces/IClientPayload.md#devicepairingdata)

***

### dnsSource?

> `optional` **dnsSource**: `null` \| [`IDNSSource`](../namespaces/ClientPayload/interfaces/IDNSSource.md)

Defined in: [WAProto/index.d.ts:2924](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2924)

ClientPayload dnsSource.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`dnsSource`](../interfaces/IClientPayload.md#dnssource)

***

### fbAppId

> **fbAppId**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:2954](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2954)

ClientPayload fbAppId.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`fbAppId`](../interfaces/IClientPayload.md#fbappid)

***

### fbCat

> **fbCat**: `Uint8Array`

Defined in: [WAProto/index.d.ts:2939](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2939)

ClientPayload fbCat.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`fbCat`](../interfaces/IClientPayload.md#fbcat)

***

### fbDeviceId

> **fbDeviceId**: `Uint8Array`

Defined in: [WAProto/index.d.ts:2957](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2957)

ClientPayload fbDeviceId.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`fbDeviceId`](../interfaces/IClientPayload.md#fbdeviceid)

***

### fbUserAgent

> **fbUserAgent**: `Uint8Array`

Defined in: [WAProto/index.d.ts:2942](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2942)

ClientPayload fbUserAgent.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`fbUserAgent`](../interfaces/IClientPayload.md#fbuseragent)

***

### interopData?

> `optional` **interopData**: `null` \| [`IInteropData`](../namespaces/ClientPayload/interfaces/IInteropData.md)

Defined in: [WAProto/index.d.ts:2972](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2972)

ClientPayload interopData.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`interopData`](../interfaces/IClientPayload.md#interopdata)

***

### iosAppExtension

> **iosAppExtension**: [`IOSAppExtension`](../namespaces/ClientPayload/enumerations/IOSAppExtension.md)

Defined in: [WAProto/index.d.ts:2951](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2951)

ClientPayload iosAppExtension.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`iosAppExtension`](../interfaces/IClientPayload.md#iosappextension)

***

### lc

> **lc**: `number`

Defined in: [WAProto/index.d.ts:2948](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2948)

ClientPayload lc.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`lc`](../interfaces/IClientPayload.md#lc)

***

### memClass

> **memClass**: `number`

Defined in: [WAProto/index.d.ts:2969](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2969)

ClientPayload memClass.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`memClass`](../interfaces/IClientPayload.md#memclass)

***

### oc

> **oc**: `boolean`

Defined in: [WAProto/index.d.ts:2945](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2945)

ClientPayload oc.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`oc`](../interfaces/IClientPayload.md#oc)

***

### paddingBytes

> **paddingBytes**: `Uint8Array`

Defined in: [WAProto/index.d.ts:2963](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2963)

ClientPayload paddingBytes.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`paddingBytes`](../interfaces/IClientPayload.md#paddingbytes)

***

### passive

> **passive**: `boolean`

Defined in: [WAProto/index.d.ts:2897](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2897)

ClientPayload passive.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`passive`](../interfaces/IClientPayload.md#passive)

***

### product

> **product**: [`Product`](../namespaces/ClientPayload/enumerations/Product.md)

Defined in: [WAProto/index.d.ts:2936](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2936)

ClientPayload product.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`product`](../interfaces/IClientPayload.md#product)

***

### pull

> **pull**: `boolean`

Defined in: [WAProto/index.d.ts:2960](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2960)

ClientPayload pull.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`pull`](../interfaces/IClientPayload.md#pull)

***

### pushName

> **pushName**: `string`

Defined in: [WAProto/index.d.ts:2906](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2906)

ClientPayload pushName.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`pushName`](../interfaces/IClientPayload.md#pushname)

***

### sessionId

> **sessionId**: `number`

Defined in: [WAProto/index.d.ts:2909](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2909)

ClientPayload sessionId.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`sessionId`](../interfaces/IClientPayload.md#sessionid)

***

### shards

> **shards**: `number`[]

Defined in: [WAProto/index.d.ts:2921](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2921)

ClientPayload shards.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`shards`](../interfaces/IClientPayload.md#shards)

***

### shortConnect

> **shortConnect**: `boolean`

Defined in: [WAProto/index.d.ts:2912](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2912)

ClientPayload shortConnect.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`shortConnect`](../interfaces/IClientPayload.md#shortconnect)

***

### userAgent?

> `optional` **userAgent**: `null` \| [`IUserAgent`](../namespaces/ClientPayload/interfaces/IUserAgent.md)

Defined in: [WAProto/index.d.ts:2900](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2900)

ClientPayload userAgent.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`userAgent`](../interfaces/IClientPayload.md#useragent)

***

### username

> **username**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:2894](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2894)

ClientPayload username.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`username`](../interfaces/IClientPayload.md#username)

***

### webInfo?

> `optional` **webInfo**: `null` \| [`IWebInfo`](../namespaces/ClientPayload/interfaces/IWebInfo.md)

Defined in: [WAProto/index.d.ts:2903](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2903)

ClientPayload webInfo.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`webInfo`](../interfaces/IClientPayload.md#webinfo)

***

### yearClass

> **yearClass**: `number`

Defined in: [WAProto/index.d.ts:2966](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2966)

ClientPayload yearClass.

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`yearClass`](../interfaces/IClientPayload.md#yearclass)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3042](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3042)

Converts this ClientPayload to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ClientPayload`](ClientPayload.md)

Defined in: [WAProto/index.d.ts:2979](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2979)

Creates a new ClientPayload instance using the specified properties.

#### Parameters

##### properties?

[`IClientPayload`](../interfaces/IClientPayload.md)

Properties to set

#### Returns

[`ClientPayload`](ClientPayload.md)

ClientPayload instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ClientPayload`](ClientPayload.md)

Defined in: [WAProto/index.d.ts:3005](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3005)

Decodes a ClientPayload message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ClientPayload`](ClientPayload.md)

ClientPayload

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ClientPayload`](ClientPayload.md)

Defined in: [WAProto/index.d.ts:3014](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3014)

Decodes a ClientPayload message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ClientPayload`](ClientPayload.md)

ClientPayload

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2987](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2987)

Encodes the specified ClientPayload message. Does not implicitly [verify](ClientPayload.md#verify) messages.

#### Parameters

##### message

[`IClientPayload`](../interfaces/IClientPayload.md)

ClientPayload message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2995](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L2995)

Encodes the specified ClientPayload message, length delimited. Does not implicitly [verify](ClientPayload.md#verify) messages.

#### Parameters

##### message

[`IClientPayload`](../interfaces/IClientPayload.md)

ClientPayload message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ClientPayload`](ClientPayload.md)

Defined in: [WAProto/index.d.ts:3028](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3028)

Creates a ClientPayload message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ClientPayload`](ClientPayload.md)

ClientPayload

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:3036](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3036)

Creates a plain object from a ClientPayload message. Also converts values to other types if specified.

#### Parameters

##### message

[`ClientPayload`](ClientPayload.md)

ClientPayload

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3021](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L3021)

Verifies a ClientPayload message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

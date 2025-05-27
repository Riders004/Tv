# Class: DisappearingMode

Defined in: [WAProto/index.d.ts:6123](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6123)

Represents a DisappearingMode.

## Implements

- [`IDisappearingMode`](../interfaces/IDisappearingMode.md)

## Constructors

### new DisappearingMode()

> **new DisappearingMode**(`properties`?): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:6129](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6129)

Constructs a new DisappearingMode.

#### Parameters

##### properties?

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

Properties to set

#### Returns

[`DisappearingMode`](DisappearingMode.md)

## Properties

### initiatedByMe

> **initiatedByMe**: `boolean`

Defined in: [WAProto/index.d.ts:6141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6141)

DisappearingMode initiatedByMe.

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`initiatedByMe`](../interfaces/IDisappearingMode.md#initiatedbyme)

***

### initiator

> **initiator**: [`Initiator`](../namespaces/DisappearingMode/enumerations/Initiator.md)

Defined in: [WAProto/index.d.ts:6132](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6132)

DisappearingMode initiator.

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`initiator`](../interfaces/IDisappearingMode.md#initiator)

***

### initiatorDeviceJid

> **initiatorDeviceJid**: `string`

Defined in: [WAProto/index.d.ts:6138](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6138)

DisappearingMode initiatorDeviceJid.

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`initiatorDeviceJid`](../interfaces/IDisappearingMode.md#initiatordevicejid)

***

### trigger

> **trigger**: [`Trigger`](../namespaces/DisappearingMode/enumerations/Trigger.md)

Defined in: [WAProto/index.d.ts:6135](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6135)

DisappearingMode trigger.

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`trigger`](../interfaces/IDisappearingMode.md#trigger)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6211](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6211)

Converts this DisappearingMode to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:6148](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6148)

Creates a new DisappearingMode instance using the specified properties.

#### Parameters

##### properties?

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

Properties to set

#### Returns

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:6174](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6174)

Decodes a DisappearingMode message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:6183](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6183)

Decodes a DisappearingMode message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6156](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6156)

Encodes the specified DisappearingMode message. Does not implicitly [verify](DisappearingMode.md#verify) messages.

#### Parameters

##### message

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

DisappearingMode message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6164](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6164)

Encodes the specified DisappearingMode message, length delimited. Does not implicitly [verify](DisappearingMode.md#verify) messages.

#### Parameters

##### message

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

DisappearingMode message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:6197](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6197)

Creates a DisappearingMode message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:6205](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6205)

Creates a plain object from a DisappearingMode message. Also converts values to other types if specified.

#### Parameters

##### message

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6190](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L6190)

Verifies a DisappearingMode message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

# Class: ScheduledCallCreationMessage

Defined in: [WAProto/index.d.ts:21734](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21734)

Represents a ScheduledCallCreationMessage.

## Implements

- [`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

## Constructors

### new ScheduledCallCreationMessage()

> **new ScheduledCallCreationMessage**(`properties`?): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:21740](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21740)

Constructs a new ScheduledCallCreationMessage.

#### Parameters

##### properties?

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

Properties to set

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

## Properties

### callType

> **callType**: [`CallType`](../namespaces/ScheduledCallCreationMessage/enumerations/CallType.md)

Defined in: [WAProto/index.d.ts:21746](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21746)

ScheduledCallCreationMessage callType.

#### Implementation of

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md).[`callType`](../interfaces/IScheduledCallCreationMessage.md#calltype)

***

### scheduledTimestampMs

> **scheduledTimestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:21743](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21743)

ScheduledCallCreationMessage scheduledTimestampMs.

#### Implementation of

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md).[`scheduledTimestampMs`](../interfaces/IScheduledCallCreationMessage.md#scheduledtimestampms)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:21749](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21749)

ScheduledCallCreationMessage title.

#### Implementation of

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md).[`title`](../interfaces/IScheduledCallCreationMessage.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21819](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21819)

Converts this ScheduledCallCreationMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:21756](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21756)

Creates a new ScheduledCallCreationMessage instance using the specified properties.

#### Parameters

##### properties?

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

Properties to set

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:21782](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21782)

Decodes a ScheduledCallCreationMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:21791](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21791)

Decodes a ScheduledCallCreationMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21764](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21764)

Encodes the specified ScheduledCallCreationMessage message. Does not implicitly [verify](ScheduledCallCreationMessage.md#verify) messages.

#### Parameters

##### message

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

ScheduledCallCreationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21772](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21772)

Encodes the specified ScheduledCallCreationMessage message, length delimited. Does not implicitly [verify](ScheduledCallCreationMessage.md#verify) messages.

#### Parameters

##### message

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

ScheduledCallCreationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:21805](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21805)

Creates a ScheduledCallCreationMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:21813](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21813)

Creates a plain object from a ScheduledCallCreationMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21798](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21798)

Verifies a ScheduledCallCreationMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

# Class: CallLogMessage

Defined in: [WAProto/index.d.ts:11922](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11922)

Represents a CallLogMessage.

## Implements

- [`ICallLogMessage`](../interfaces/ICallLogMessage.md)

## Constructors

### new CallLogMessage()

> **new CallLogMessage**(`properties`?): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:11928](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11928)

Constructs a new CallLogMessage.

#### Parameters

##### properties?

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

Properties to set

#### Returns

[`CallLogMessage`](CallLogMessage.md)

## Properties

### callOutcome

> **callOutcome**: [`CallOutcome`](../namespaces/CallLogMessage/enumerations/CallOutcome.md)

Defined in: [WAProto/index.d.ts:11934](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11934)

CallLogMessage callOutcome.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`callOutcome`](../interfaces/ICallLogMessage.md#calloutcome)

***

### callType

> **callType**: [`CallType`](../namespaces/CallLogMessage/enumerations/CallType.md)

Defined in: [WAProto/index.d.ts:11940](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11940)

CallLogMessage callType.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`callType`](../interfaces/ICallLogMessage.md#calltype)

***

### durationSecs

> **durationSecs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:11937](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11937)

CallLogMessage durationSecs.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`durationSecs`](../interfaces/ICallLogMessage.md#durationsecs)

***

### isVideo

> **isVideo**: `boolean`

Defined in: [WAProto/index.d.ts:11931](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11931)

CallLogMessage isVideo.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`isVideo`](../interfaces/ICallLogMessage.md#isvideo)

***

### participants

> **participants**: [`ICallParticipant`](../namespaces/CallLogMessage/interfaces/ICallParticipant.md)[]

Defined in: [WAProto/index.d.ts:11943](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11943)

CallLogMessage participants.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`participants`](../interfaces/ICallLogMessage.md#participants)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12013](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12013)

Converts this CallLogMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:11950](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11950)

Creates a new CallLogMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

Properties to set

#### Returns

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:11976](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11976)

Decodes a CallLogMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:11985](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11985)

Decodes a CallLogMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11958](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11958)

Encodes the specified CallLogMessage message. Does not implicitly [verify](CallLogMessage.md#verify) messages.

#### Parameters

##### message

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

CallLogMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11966](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11966)

Encodes the specified CallLogMessage message, length delimited. Does not implicitly [verify](CallLogMessage.md#verify) messages.

#### Parameters

##### message

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

CallLogMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:11999](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11999)

Creates a CallLogMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:12007](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L12007)

Creates a plain object from a CallLogMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11992](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L11992)

Verifies a CallLogMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

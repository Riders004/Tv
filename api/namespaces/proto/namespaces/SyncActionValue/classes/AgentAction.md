# Class: AgentAction

Defined in: [WAProto/index.d.ts:29863](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29863)

Represents an AgentAction.

## Implements

- [`IAgentAction`](../interfaces/IAgentAction.md)

## Constructors

### new AgentAction()

> **new AgentAction**(`properties`?): [`AgentAction`](AgentAction.md)

Defined in: [WAProto/index.d.ts:29869](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29869)

Constructs a new AgentAction.

#### Parameters

##### properties?

[`IAgentAction`](../interfaces/IAgentAction.md)

Properties to set

#### Returns

[`AgentAction`](AgentAction.md)

## Properties

### deviceID

> **deviceID**: `number`

Defined in: [WAProto/index.d.ts:29875](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29875)

AgentAction deviceID.

#### Implementation of

[`IAgentAction`](../interfaces/IAgentAction.md).[`deviceID`](../interfaces/IAgentAction.md#deviceid)

***

### isDeleted

> **isDeleted**: `boolean`

Defined in: [WAProto/index.d.ts:29878](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29878)

AgentAction isDeleted.

#### Implementation of

[`IAgentAction`](../interfaces/IAgentAction.md).[`isDeleted`](../interfaces/IAgentAction.md#isdeleted)

***

### name

> **name**: `string`

Defined in: [WAProto/index.d.ts:29872](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29872)

AgentAction name.

#### Implementation of

[`IAgentAction`](../interfaces/IAgentAction.md).[`name`](../interfaces/IAgentAction.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29948](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29948)

Converts this AgentAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AgentAction`](AgentAction.md)

Defined in: [WAProto/index.d.ts:29885](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29885)

Creates a new AgentAction instance using the specified properties.

#### Parameters

##### properties?

[`IAgentAction`](../interfaces/IAgentAction.md)

Properties to set

#### Returns

[`AgentAction`](AgentAction.md)

AgentAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AgentAction`](AgentAction.md)

Defined in: [WAProto/index.d.ts:29911](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29911)

Decodes an AgentAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AgentAction`](AgentAction.md)

AgentAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AgentAction`](AgentAction.md)

Defined in: [WAProto/index.d.ts:29920](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29920)

Decodes an AgentAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AgentAction`](AgentAction.md)

AgentAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29893](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29893)

Encodes the specified AgentAction message. Does not implicitly [verify](AgentAction.md#verify) messages.

#### Parameters

##### message

[`IAgentAction`](../interfaces/IAgentAction.md)

AgentAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29901](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29901)

Encodes the specified AgentAction message, length delimited. Does not implicitly [verify](AgentAction.md#verify) messages.

#### Parameters

##### message

[`IAgentAction`](../interfaces/IAgentAction.md)

AgentAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AgentAction`](AgentAction.md)

Defined in: [WAProto/index.d.ts:29934](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29934)

Creates an AgentAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AgentAction`](AgentAction.md)

AgentAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:29942](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29942)

Creates a plain object from an AgentAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`AgentAction`](AgentAction.md)

AgentAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29927](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L29927)

Verifies an AgentAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

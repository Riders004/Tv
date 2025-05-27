# Class: SessionStructure

Defined in: [WAProto/index.d.ts:28265](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28265)

Represents a SessionStructure.

## Implements

- [`ISessionStructure`](../interfaces/ISessionStructure.md)

## Constructors

### new SessionStructure()

> **new SessionStructure**(`properties`?): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:28271](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28271)

Constructs a new SessionStructure.

#### Parameters

##### properties?

[`ISessionStructure`](../interfaces/ISessionStructure.md)

Properties to set

#### Returns

[`SessionStructure`](SessionStructure.md)

## Properties

### aliceBaseKey

> **aliceBaseKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28310](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28310)

SessionStructure aliceBaseKey.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`aliceBaseKey`](../interfaces/ISessionStructure.md#alicebasekey)

***

### localIdentityPublic

> **localIdentityPublic**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28277](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28277)

SessionStructure localIdentityPublic.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`localIdentityPublic`](../interfaces/ISessionStructure.md#localidentitypublic)

***

### localRegistrationId

> **localRegistrationId**: `number`

Defined in: [WAProto/index.d.ts:28304](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28304)

SessionStructure localRegistrationId.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`localRegistrationId`](../interfaces/ISessionStructure.md#localregistrationid)

***

### needsRefresh

> **needsRefresh**: `boolean`

Defined in: [WAProto/index.d.ts:28307](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28307)

SessionStructure needsRefresh.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`needsRefresh`](../interfaces/ISessionStructure.md#needsrefresh)

***

### pendingKeyExchange?

> `optional` **pendingKeyExchange**: `null` \| [`IPendingKeyExchange`](../namespaces/SessionStructure/interfaces/IPendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:28295](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28295)

SessionStructure pendingKeyExchange.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`pendingKeyExchange`](../interfaces/ISessionStructure.md#pendingkeyexchange)

***

### pendingPreKey?

> `optional` **pendingPreKey**: `null` \| [`IPendingPreKey`](../namespaces/SessionStructure/interfaces/IPendingPreKey.md)

Defined in: [WAProto/index.d.ts:28298](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28298)

SessionStructure pendingPreKey.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`pendingPreKey`](../interfaces/ISessionStructure.md#pendingprekey)

***

### previousCounter

> **previousCounter**: `number`

Defined in: [WAProto/index.d.ts:28286](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28286)

SessionStructure previousCounter.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`previousCounter`](../interfaces/ISessionStructure.md#previouscounter)

***

### receiverChains

> **receiverChains**: [`IChain`](../namespaces/SessionStructure/interfaces/IChain.md)[]

Defined in: [WAProto/index.d.ts:28292](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28292)

SessionStructure receiverChains.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`receiverChains`](../interfaces/ISessionStructure.md#receiverchains)

***

### remoteIdentityPublic

> **remoteIdentityPublic**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28280](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28280)

SessionStructure remoteIdentityPublic.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`remoteIdentityPublic`](../interfaces/ISessionStructure.md#remoteidentitypublic)

***

### remoteRegistrationId

> **remoteRegistrationId**: `number`

Defined in: [WAProto/index.d.ts:28301](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28301)

SessionStructure remoteRegistrationId.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`remoteRegistrationId`](../interfaces/ISessionStructure.md#remoteregistrationid)

***

### rootKey

> **rootKey**: `Uint8Array`

Defined in: [WAProto/index.d.ts:28283](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28283)

SessionStructure rootKey.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`rootKey`](../interfaces/ISessionStructure.md#rootkey)

***

### senderChain?

> `optional` **senderChain**: `null` \| [`IChain`](../namespaces/SessionStructure/interfaces/IChain.md)

Defined in: [WAProto/index.d.ts:28289](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28289)

SessionStructure senderChain.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`senderChain`](../interfaces/ISessionStructure.md#senderchain)

***

### sessionVersion

> **sessionVersion**: `number`

Defined in: [WAProto/index.d.ts:28274](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28274)

SessionStructure sessionVersion.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`sessionVersion`](../interfaces/ISessionStructure.md#sessionversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28380](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28380)

Converts this SessionStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:28317](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28317)

Creates a new SessionStructure instance using the specified properties.

#### Parameters

##### properties?

[`ISessionStructure`](../interfaces/ISessionStructure.md)

Properties to set

#### Returns

[`SessionStructure`](SessionStructure.md)

SessionStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:28343](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28343)

Decodes a SessionStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SessionStructure`](SessionStructure.md)

SessionStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:28352](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28352)

Decodes a SessionStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SessionStructure`](SessionStructure.md)

SessionStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28325](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28325)

Encodes the specified SessionStructure message. Does not implicitly [verify](SessionStructure.md#verify) messages.

#### Parameters

##### message

[`ISessionStructure`](../interfaces/ISessionStructure.md)

SessionStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28333](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28333)

Encodes the specified SessionStructure message, length delimited. Does not implicitly [verify](SessionStructure.md#verify) messages.

#### Parameters

##### message

[`ISessionStructure`](../interfaces/ISessionStructure.md)

SessionStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:28366](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28366)

Creates a SessionStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SessionStructure`](SessionStructure.md)

SessionStructure

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:28374](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28374)

Creates a plain object from a SessionStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`SessionStructure`](SessionStructure.md)

SessionStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28359](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L28359)

Verifies a SessionStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

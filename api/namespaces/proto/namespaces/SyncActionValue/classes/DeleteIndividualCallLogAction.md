# Class: DeleteIndividualCallLogAction

Defined in: [WAProto/index.d.ts:31090](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31090)

Represents a DeleteIndividualCallLogAction.

## Implements

- [`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

## Constructors

### new DeleteIndividualCallLogAction()

> **new DeleteIndividualCallLogAction**(`properties`?): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:31096](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31096)

Constructs a new DeleteIndividualCallLogAction.

#### Parameters

##### properties?

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

Properties to set

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

## Properties

### isIncoming

> **isIncoming**: `boolean`

Defined in: [WAProto/index.d.ts:31102](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31102)

DeleteIndividualCallLogAction isIncoming.

#### Implementation of

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md).[`isIncoming`](../interfaces/IDeleteIndividualCallLogAction.md#isincoming)

***

### peerJid

> **peerJid**: `string`

Defined in: [WAProto/index.d.ts:31099](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31099)

DeleteIndividualCallLogAction peerJid.

#### Implementation of

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md).[`peerJid`](../interfaces/IDeleteIndividualCallLogAction.md#peerjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31172](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31172)

Converts this DeleteIndividualCallLogAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:31109](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31109)

Creates a new DeleteIndividualCallLogAction instance using the specified properties.

#### Parameters

##### properties?

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

Properties to set

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:31135](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31135)

Decodes a DeleteIndividualCallLogAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:31144](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31144)

Decodes a DeleteIndividualCallLogAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31117](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31117)

Encodes the specified DeleteIndividualCallLogAction message. Does not implicitly [verify](DeleteIndividualCallLogAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31125](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31125)

Encodes the specified DeleteIndividualCallLogAction message, length delimited. Does not implicitly [verify](DeleteIndividualCallLogAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:31158](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31158)

Creates a DeleteIndividualCallLogAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:31166](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31166)

Creates a plain object from a DeleteIndividualCallLogAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31151](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31151)

Verifies a DeleteIndividualCallLogAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

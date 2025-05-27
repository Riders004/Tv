# Class: UserStatusMuteAction

Defined in: [WAProto/index.d.ts:34189](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34189)

Represents a UserStatusMuteAction.

## Implements

- [`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

## Constructors

### new UserStatusMuteAction()

> **new UserStatusMuteAction**(`properties`?): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:34195](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34195)

Constructs a new UserStatusMuteAction.

#### Parameters

##### properties?

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

Properties to set

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

## Properties

### muted

> **muted**: `boolean`

Defined in: [WAProto/index.d.ts:34198](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34198)

UserStatusMuteAction muted.

#### Implementation of

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md).[`muted`](../interfaces/IUserStatusMuteAction.md#muted)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34268](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34268)

Converts this UserStatusMuteAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:34205](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34205)

Creates a new UserStatusMuteAction instance using the specified properties.

#### Parameters

##### properties?

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

Properties to set

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:34231](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34231)

Decodes a UserStatusMuteAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:34240](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34240)

Decodes a UserStatusMuteAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34213](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34213)

Encodes the specified UserStatusMuteAction message. Does not implicitly [verify](UserStatusMuteAction.md#verify) messages.

#### Parameters

##### message

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

UserStatusMuteAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34221](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34221)

Encodes the specified UserStatusMuteAction message, length delimited. Does not implicitly [verify](UserStatusMuteAction.md#verify) messages.

#### Parameters

##### message

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

UserStatusMuteAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:34254](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34254)

Creates a UserStatusMuteAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:34262](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34262)

Creates a plain object from a UserStatusMuteAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34247](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L34247)

Verifies a UserStatusMuteAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

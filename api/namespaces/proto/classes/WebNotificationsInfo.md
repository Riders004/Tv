# Class: WebNotificationsInfo

Defined in: [WAProto/index.d.ts:36926](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36926)

Represents a WebNotificationsInfo.

## Implements

- [`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

## Constructors

### new WebNotificationsInfo()

> **new WebNotificationsInfo**(`properties`?): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:36932](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36932)

Constructs a new WebNotificationsInfo.

#### Parameters

##### properties?

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

Properties to set

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

## Properties

### notifyMessageCount

> **notifyMessageCount**: `number`

Defined in: [WAProto/index.d.ts:36941](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36941)

WebNotificationsInfo notifyMessageCount.

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`notifyMessageCount`](../interfaces/IWebNotificationsInfo.md#notifymessagecount)

***

### notifyMessages

> **notifyMessages**: [`IWebMessageInfo`](../interfaces/IWebMessageInfo.md)[]

Defined in: [WAProto/index.d.ts:36944](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36944)

WebNotificationsInfo notifyMessages.

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`notifyMessages`](../interfaces/IWebNotificationsInfo.md#notifymessages)

***

### timestamp

> **timestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:36935](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36935)

WebNotificationsInfo timestamp.

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`timestamp`](../interfaces/IWebNotificationsInfo.md#timestamp)

***

### unreadChats

> **unreadChats**: `number`

Defined in: [WAProto/index.d.ts:36938](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36938)

WebNotificationsInfo unreadChats.

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`unreadChats`](../interfaces/IWebNotificationsInfo.md#unreadchats)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:37014](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L37014)

Converts this WebNotificationsInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:36951](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36951)

Creates a new WebNotificationsInfo instance using the specified properties.

#### Parameters

##### properties?

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

Properties to set

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:36977](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36977)

Decodes a WebNotificationsInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:36986](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36986)

Decodes a WebNotificationsInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36959](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36959)

Encodes the specified WebNotificationsInfo message. Does not implicitly [verify](WebNotificationsInfo.md#verify) messages.

#### Parameters

##### message

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

WebNotificationsInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36967](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36967)

Encodes the specified WebNotificationsInfo message, length delimited. Does not implicitly [verify](WebNotificationsInfo.md#verify) messages.

#### Parameters

##### message

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

WebNotificationsInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:37000](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L37000)

Creates a WebNotificationsInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:37008](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L37008)

Creates a plain object from a WebNotificationsInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:36993](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L36993)

Verifies a WebNotificationsInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

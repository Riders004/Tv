# Class: SecurityNotificationSetting

Defined in: [WAProto/index.d.ts:33279](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33279)

Represents a SecurityNotificationSetting.

## Implements

- [`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

## Constructors

### new SecurityNotificationSetting()

> **new SecurityNotificationSetting**(`properties`?): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:33285](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33285)

Constructs a new SecurityNotificationSetting.

#### Parameters

##### properties?

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

Properties to set

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

## Properties

### showNotification

> **showNotification**: `boolean`

Defined in: [WAProto/index.d.ts:33288](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33288)

SecurityNotificationSetting showNotification.

#### Implementation of

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md).[`showNotification`](../interfaces/ISecurityNotificationSetting.md#shownotification)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33358](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33358)

Converts this SecurityNotificationSetting to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:33295](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33295)

Creates a new SecurityNotificationSetting instance using the specified properties.

#### Parameters

##### properties?

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

Properties to set

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:33321](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33321)

Decodes a SecurityNotificationSetting message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:33330](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33330)

Decodes a SecurityNotificationSetting message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33303](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33303)

Encodes the specified SecurityNotificationSetting message. Does not implicitly [verify](SecurityNotificationSetting.md#verify) messages.

#### Parameters

##### message

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

SecurityNotificationSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33311](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33311)

Encodes the specified SecurityNotificationSetting message, length delimited. Does not implicitly [verify](SecurityNotificationSetting.md#verify) messages.

#### Parameters

##### message

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

SecurityNotificationSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:33344](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33344)

Creates a SecurityNotificationSetting message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33352](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33352)

Creates a plain object from a SecurityNotificationSetting message. Also converts values to other types if specified.

#### Parameters

##### message

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33337](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33337)

Verifies a SecurityNotificationSetting message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

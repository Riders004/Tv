# Class: MessageContextInfo

Defined in: [WAProto/index.d.ts:23315](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23315)

Represents a MessageContextInfo.

## Implements

- [`IMessageContextInfo`](../interfaces/IMessageContextInfo.md)

## Constructors

### new MessageContextInfo()

> **new MessageContextInfo**(`properties`?): [`MessageContextInfo`](MessageContextInfo.md)

Defined in: [WAProto/index.d.ts:23321](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23321)

Constructs a new MessageContextInfo.

#### Parameters

##### properties?

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md)

Properties to set

#### Returns

[`MessageContextInfo`](MessageContextInfo.md)

## Properties

### botMessageSecret

> **botMessageSecret**: `Uint8Array`

Defined in: [WAProto/index.d.ts:23339](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23339)

MessageContextInfo botMessageSecret.

#### Implementation of

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md).[`botMessageSecret`](../interfaces/IMessageContextInfo.md#botmessagesecret)

***

### botMetadata?

> `optional` **botMetadata**: `null` \| [`IBotMetadata`](../interfaces/IBotMetadata.md)

Defined in: [WAProto/index.d.ts:23342](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23342)

MessageContextInfo botMetadata.

#### Implementation of

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md).[`botMetadata`](../interfaces/IMessageContextInfo.md#botmetadata)

***

### deviceListMetadata?

> `optional` **deviceListMetadata**: `null` \| [`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:23324](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23324)

MessageContextInfo deviceListMetadata.

#### Implementation of

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md).[`deviceListMetadata`](../interfaces/IMessageContextInfo.md#devicelistmetadata)

***

### deviceListMetadataVersion

> **deviceListMetadataVersion**: `number`

Defined in: [WAProto/index.d.ts:23327](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23327)

MessageContextInfo deviceListMetadataVersion.

#### Implementation of

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md).[`deviceListMetadataVersion`](../interfaces/IMessageContextInfo.md#devicelistmetadataversion)

***

### messageAddOnDurationInSecs

> **messageAddOnDurationInSecs**: `number`

Defined in: [WAProto/index.d.ts:23336](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23336)

MessageContextInfo messageAddOnDurationInSecs.

#### Implementation of

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md).[`messageAddOnDurationInSecs`](../interfaces/IMessageContextInfo.md#messageaddondurationinsecs)

***

### messageSecret

> **messageSecret**: `Uint8Array`

Defined in: [WAProto/index.d.ts:23330](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23330)

MessageContextInfo messageSecret.

#### Implementation of

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md).[`messageSecret`](../interfaces/IMessageContextInfo.md#messagesecret)

***

### paddingBytes

> **paddingBytes**: `Uint8Array`

Defined in: [WAProto/index.d.ts:23333](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23333)

MessageContextInfo paddingBytes.

#### Implementation of

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md).[`paddingBytes`](../interfaces/IMessageContextInfo.md#paddingbytes)

***

### reportingTokenVersion

> **reportingTokenVersion**: `number`

Defined in: [WAProto/index.d.ts:23345](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23345)

MessageContextInfo reportingTokenVersion.

#### Implementation of

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md).[`reportingTokenVersion`](../interfaces/IMessageContextInfo.md#reportingtokenversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:23415](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23415)

Converts this MessageContextInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageContextInfo`](MessageContextInfo.md)

Defined in: [WAProto/index.d.ts:23352](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23352)

Creates a new MessageContextInfo instance using the specified properties.

#### Parameters

##### properties?

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md)

Properties to set

#### Returns

[`MessageContextInfo`](MessageContextInfo.md)

MessageContextInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageContextInfo`](MessageContextInfo.md)

Defined in: [WAProto/index.d.ts:23378](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23378)

Decodes a MessageContextInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageContextInfo`](MessageContextInfo.md)

MessageContextInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageContextInfo`](MessageContextInfo.md)

Defined in: [WAProto/index.d.ts:23387](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23387)

Decodes a MessageContextInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageContextInfo`](MessageContextInfo.md)

MessageContextInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23360](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23360)

Encodes the specified MessageContextInfo message. Does not implicitly [verify](MessageContextInfo.md#verify) messages.

#### Parameters

##### message

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md)

MessageContextInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23368](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23368)

Encodes the specified MessageContextInfo message, length delimited. Does not implicitly [verify](MessageContextInfo.md#verify) messages.

#### Parameters

##### message

[`IMessageContextInfo`](../interfaces/IMessageContextInfo.md)

MessageContextInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageContextInfo`](MessageContextInfo.md)

Defined in: [WAProto/index.d.ts:23401](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23401)

Creates a MessageContextInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageContextInfo`](MessageContextInfo.md)

MessageContextInfo

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:23409](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23409)

Creates a plain object from a MessageContextInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageContextInfo`](MessageContextInfo.md)

MessageContextInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:23394](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L23394)

Verifies a MessageContextInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

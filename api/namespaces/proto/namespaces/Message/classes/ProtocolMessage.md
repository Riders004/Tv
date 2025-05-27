# Class: ProtocolMessage

Defined in: [WAProto/index.d.ts:21141](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21141)

Represents a ProtocolMessage.

## Implements

- [`IProtocolMessage`](../interfaces/IProtocolMessage.md)

## Constructors

### new ProtocolMessage()

> **new ProtocolMessage**(`properties`?): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:21147](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21147)

Constructs a new ProtocolMessage.

#### Parameters

##### properties?

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

Properties to set

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

## Properties

### appStateFatalExceptionNotification?

> `optional` **appStateFatalExceptionNotification**: `null` \| [`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:21174](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21174)

ProtocolMessage appStateFatalExceptionNotification.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`appStateFatalExceptionNotification`](../interfaces/IProtocolMessage.md#appstatefatalexceptionnotification)

***

### appStateSyncKeyRequest?

> `optional` **appStateSyncKeyRequest**: `null` \| [`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:21168](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21168)

ProtocolMessage appStateSyncKeyRequest.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`appStateSyncKeyRequest`](../interfaces/IProtocolMessage.md#appstatesynckeyrequest)

***

### appStateSyncKeyShare?

> `optional` **appStateSyncKeyShare**: `null` \| [`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:21165](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21165)

ProtocolMessage appStateSyncKeyShare.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`appStateSyncKeyShare`](../interfaces/IProtocolMessage.md#appstatesynckeyshare)

***

### botFeedbackMessage?

> `optional` **botFeedbackMessage**: `null` \| [`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:21192](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21192)

ProtocolMessage botFeedbackMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`botFeedbackMessage`](../interfaces/IProtocolMessage.md#botfeedbackmessage)

***

### disappearingMode?

> `optional` **disappearingMode**: `null` \| [`IDisappearingMode`](../../../interfaces/IDisappearingMode.md)

Defined in: [WAProto/index.d.ts:21177](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21177)

ProtocolMessage disappearingMode.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`disappearingMode`](../interfaces/IProtocolMessage.md#disappearingmode)

***

### editedMessage?

> `optional` **editedMessage**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:21180](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21180)

ProtocolMessage editedMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`editedMessage`](../interfaces/IProtocolMessage.md#editedmessage)

***

### ephemeralExpiration

> **ephemeralExpiration**: `number`

Defined in: [WAProto/index.d.ts:21156](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21156)

ProtocolMessage ephemeralExpiration.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`ephemeralExpiration`](../interfaces/IProtocolMessage.md#ephemeralexpiration)

***

### ephemeralSettingTimestamp

> **ephemeralSettingTimestamp**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:21159](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21159)

ProtocolMessage ephemeralSettingTimestamp.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`ephemeralSettingTimestamp`](../interfaces/IProtocolMessage.md#ephemeralsettingtimestamp)

***

### historySyncNotification?

> `optional` **historySyncNotification**: `null` \| [`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md)

Defined in: [WAProto/index.d.ts:21162](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21162)

ProtocolMessage historySyncNotification.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`historySyncNotification`](../interfaces/IProtocolMessage.md#historysyncnotification)

***

### initialSecurityNotificationSettingSync?

> `optional` **initialSecurityNotificationSettingSync**: `null` \| [`IInitialSecurityNotificationSettingSync`](../interfaces/IInitialSecurityNotificationSettingSync.md)

Defined in: [WAProto/index.d.ts:21171](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21171)

ProtocolMessage initialSecurityNotificationSettingSync.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`initialSecurityNotificationSettingSync`](../interfaces/IProtocolMessage.md#initialsecuritynotificationsettingsync)

***

### invokerJid

> **invokerJid**: `string`

Defined in: [WAProto/index.d.ts:21195](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21195)

ProtocolMessage invokerJid.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`invokerJid`](../interfaces/IProtocolMessage.md#invokerjid)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:21150](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21150)

ProtocolMessage key.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`key`](../interfaces/IProtocolMessage.md#key)

***

### mediaNotifyMessage?

> `optional` **mediaNotifyMessage**: `null` \| [`IMediaNotifyMessage`](../../../interfaces/IMediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:21201](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21201)

ProtocolMessage mediaNotifyMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`mediaNotifyMessage`](../interfaces/IProtocolMessage.md#medianotifymessage)

***

### peerDataOperationRequestMessage?

> `optional` **peerDataOperationRequestMessage**: `null` \| [`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:21186](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21186)

ProtocolMessage peerDataOperationRequestMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`peerDataOperationRequestMessage`](../interfaces/IProtocolMessage.md#peerdataoperationrequestmessage)

***

### peerDataOperationRequestResponseMessage?

> `optional` **peerDataOperationRequestResponseMessage**: `null` \| [`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:21189](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21189)

ProtocolMessage peerDataOperationRequestResponseMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`peerDataOperationRequestResponseMessage`](../interfaces/IProtocolMessage.md#peerdataoperationrequestresponsemessage)

***

### requestWelcomeMessageMetadata?

> `optional` **requestWelcomeMessageMetadata**: `null` \| [`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:21198](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21198)

ProtocolMessage requestWelcomeMessageMetadata.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`requestWelcomeMessageMetadata`](../interfaces/IProtocolMessage.md#requestwelcomemessagemetadata)

***

### timestampMs

> **timestampMs**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:21183](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21183)

ProtocolMessage timestampMs.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`timestampMs`](../interfaces/IProtocolMessage.md#timestampms)

***

### type

> **type**: [`Type`](../namespaces/ProtocolMessage/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:21153](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21153)

ProtocolMessage type.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`type`](../interfaces/IProtocolMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21271](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21271)

Converts this ProtocolMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:21208](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21208)

Creates a new ProtocolMessage instance using the specified properties.

#### Parameters

##### properties?

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

Properties to set

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:21234](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21234)

Decodes a ProtocolMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:21243](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21243)

Decodes a ProtocolMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21216](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21216)

Encodes the specified ProtocolMessage message. Does not implicitly [verify](ProtocolMessage.md#verify) messages.

#### Parameters

##### message

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

ProtocolMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21224](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21224)

Encodes the specified ProtocolMessage message, length delimited. Does not implicitly [verify](ProtocolMessage.md#verify) messages.

#### Parameters

##### message

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

ProtocolMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:21257](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21257)

Creates a ProtocolMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:21265](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21265)

Creates a plain object from a ProtocolMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21250](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L21250)

Verifies a ProtocolMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

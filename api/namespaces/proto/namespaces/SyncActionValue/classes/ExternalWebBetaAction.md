# Class: ExternalWebBetaAction

Defined in: [WAProto/index.d.ts:31279](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31279)

Represents an ExternalWebBetaAction.

## Implements

- [`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

## Constructors

### new ExternalWebBetaAction()

> **new ExternalWebBetaAction**(`properties`?): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:31285](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31285)

Constructs a new ExternalWebBetaAction.

#### Parameters

##### properties?

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

Properties to set

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

## Properties

### isOptIn

> **isOptIn**: `boolean`

Defined in: [WAProto/index.d.ts:31288](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31288)

ExternalWebBetaAction isOptIn.

#### Implementation of

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md).[`isOptIn`](../interfaces/IExternalWebBetaAction.md#isoptin)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31358](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31358)

Converts this ExternalWebBetaAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:31295](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31295)

Creates a new ExternalWebBetaAction instance using the specified properties.

#### Parameters

##### properties?

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

Properties to set

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:31321](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31321)

Decodes an ExternalWebBetaAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:31330](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31330)

Decodes an ExternalWebBetaAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31303](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31303)

Encodes the specified ExternalWebBetaAction message. Does not implicitly [verify](ExternalWebBetaAction.md#verify) messages.

#### Parameters

##### message

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

ExternalWebBetaAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31311](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31311)

Encodes the specified ExternalWebBetaAction message, length delimited. Does not implicitly [verify](ExternalWebBetaAction.md#verify) messages.

#### Parameters

##### message

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

ExternalWebBetaAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:31344](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31344)

Creates an ExternalWebBetaAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:31352](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31352)

Creates a plain object from an ExternalWebBetaAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31337](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L31337)

Verifies an ExternalWebBetaAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

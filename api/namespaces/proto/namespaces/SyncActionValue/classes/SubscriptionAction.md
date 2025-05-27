# Class: SubscriptionAction

Defined in: [WAProto/index.d.ts:33715](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33715)

Represents a SubscriptionAction.

## Implements

- [`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

## Constructors

### new SubscriptionAction()

> **new SubscriptionAction**(`properties`?): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:33721](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33721)

Constructs a new SubscriptionAction.

#### Parameters

##### properties?

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

Properties to set

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

## Properties

### expirationDate

> **expirationDate**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:33730](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33730)

SubscriptionAction expirationDate.

#### Implementation of

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md).[`expirationDate`](../interfaces/ISubscriptionAction.md#expirationdate)

***

### isAutoRenewing

> **isAutoRenewing**: `boolean`

Defined in: [WAProto/index.d.ts:33727](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33727)

SubscriptionAction isAutoRenewing.

#### Implementation of

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md).[`isAutoRenewing`](../interfaces/ISubscriptionAction.md#isautorenewing)

***

### isDeactivated

> **isDeactivated**: `boolean`

Defined in: [WAProto/index.d.ts:33724](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33724)

SubscriptionAction isDeactivated.

#### Implementation of

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md).[`isDeactivated`](../interfaces/ISubscriptionAction.md#isdeactivated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33800](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33800)

Converts this SubscriptionAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:33737](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33737)

Creates a new SubscriptionAction instance using the specified properties.

#### Parameters

##### properties?

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

Properties to set

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:33763](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33763)

Decodes a SubscriptionAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:33772](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33772)

Decodes a SubscriptionAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33745](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33745)

Encodes the specified SubscriptionAction message. Does not implicitly [verify](SubscriptionAction.md#verify) messages.

#### Parameters

##### message

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

SubscriptionAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33753](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33753)

Encodes the specified SubscriptionAction message, length delimited. Does not implicitly [verify](SubscriptionAction.md#verify) messages.

#### Parameters

##### message

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

SubscriptionAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:33786](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33786)

Creates a SubscriptionAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:33794](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33794)

Creates a plain object from a SubscriptionAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33779](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L33779)

Verifies a SubscriptionAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

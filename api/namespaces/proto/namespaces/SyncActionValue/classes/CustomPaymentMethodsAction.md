# Class: CustomPaymentMethodsAction

Defined in: [WAProto/index.d.ts:30907](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30907)

Represents a CustomPaymentMethodsAction.

## Implements

- [`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

## Constructors

### new CustomPaymentMethodsAction()

> **new CustomPaymentMethodsAction**(`properties`?): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:30913](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30913)

Constructs a new CustomPaymentMethodsAction.

#### Parameters

##### properties?

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

Properties to set

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

## Properties

### customPaymentMethods

> **customPaymentMethods**: [`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)[]

Defined in: [WAProto/index.d.ts:30916](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30916)

CustomPaymentMethodsAction customPaymentMethods.

#### Implementation of

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md).[`customPaymentMethods`](../interfaces/ICustomPaymentMethodsAction.md#custompaymentmethods)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30986](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30986)

Converts this CustomPaymentMethodsAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:30923](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30923)

Creates a new CustomPaymentMethodsAction instance using the specified properties.

#### Parameters

##### properties?

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

Properties to set

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:30949](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30949)

Decodes a CustomPaymentMethodsAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:30958](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30958)

Decodes a CustomPaymentMethodsAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30931](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30931)

Encodes the specified CustomPaymentMethodsAction message. Does not implicitly [verify](CustomPaymentMethodsAction.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

CustomPaymentMethodsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30939](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30939)

Encodes the specified CustomPaymentMethodsAction message, length delimited. Does not implicitly [verify](CustomPaymentMethodsAction.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

CustomPaymentMethodsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:30972](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30972)

Creates a CustomPaymentMethodsAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:30980](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30980)

Creates a plain object from a CustomPaymentMethodsAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30965](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L30965)

Verifies a CustomPaymentMethodsAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

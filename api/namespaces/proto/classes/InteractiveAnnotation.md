# Class: InteractiveAnnotation

Defined in: [WAProto/index.d.ts:8274](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8274)

Represents an InteractiveAnnotation.

## Implements

- [`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

## Constructors

### new InteractiveAnnotation()

> **new InteractiveAnnotation**(`properties`?): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:8280](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8280)

Constructs a new InteractiveAnnotation.

#### Parameters

##### properties?

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

Properties to set

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

## Properties

### action?

> `optional` **action**: `"location"` \| `"newsletter"`

Defined in: [WAProto/index.d.ts:8295](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8295)

InteractiveAnnotation action.

***

### location?

> `optional` **location**: `null` \| [`ILocation`](../interfaces/ILocation.md)

Defined in: [WAProto/index.d.ts:8289](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8289)

InteractiveAnnotation location.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`location`](../interfaces/IInteractiveAnnotation.md#location)

***

### newsletter?

> `optional` **newsletter**: `null` \| [`IForwardedNewsletterMessageInfo`](../namespaces/ContextInfo/interfaces/IForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:8292](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8292)

InteractiveAnnotation newsletter.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`newsletter`](../interfaces/IInteractiveAnnotation.md#newsletter)

***

### polygonVertices

> **polygonVertices**: [`IPoint`](../interfaces/IPoint.md)[]

Defined in: [WAProto/index.d.ts:8283](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8283)

InteractiveAnnotation polygonVertices.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`polygonVertices`](../interfaces/IInteractiveAnnotation.md#polygonvertices)

***

### shouldSkipConfirmation

> **shouldSkipConfirmation**: `boolean`

Defined in: [WAProto/index.d.ts:8286](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8286)

InteractiveAnnotation shouldSkipConfirmation.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`shouldSkipConfirmation`](../interfaces/IInteractiveAnnotation.md#shouldskipconfirmation)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8365](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8365)

Converts this InteractiveAnnotation to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:8302](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8302)

Creates a new InteractiveAnnotation instance using the specified properties.

#### Parameters

##### properties?

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

Properties to set

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:8328](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8328)

Decodes an InteractiveAnnotation message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:8337](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8337)

Decodes an InteractiveAnnotation message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8310](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8310)

Encodes the specified InteractiveAnnotation message. Does not implicitly [verify](InteractiveAnnotation.md#verify) messages.

#### Parameters

##### message

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

InteractiveAnnotation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8318](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8318)

Encodes the specified InteractiveAnnotation message, length delimited. Does not implicitly [verify](InteractiveAnnotation.md#verify) messages.

#### Parameters

##### message

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

InteractiveAnnotation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:8351](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8351)

Creates an InteractiveAnnotation message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:8359](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8359)

Creates a plain object from an InteractiveAnnotation message. Also converts values to other types if specified.

#### Parameters

##### message

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8344](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/WAProto/index.d.ts#L8344)

Verifies an InteractiveAnnotation message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not

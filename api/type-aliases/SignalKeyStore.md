# Type Alias: SignalKeyStore

> **SignalKeyStore**: `object`

Defined in: [src/Types/Auth.ts:81](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/src/Types/Auth.ts#L81)

## Type declaration

### clear()?

clear all the data in the store

#### Returns

`Awaitable`\<`void`\>

### get()

#### Type Parameters

• **T** *extends* keyof [`SignalDataTypeMap`](SignalDataTypeMap.md)

#### Parameters

##### type

`T`

##### ids

`string`[]

#### Returns

`Awaitable`\<\{\}\>

### set()

#### Parameters

##### data

[`SignalDataSet`](SignalDataSet.md)

#### Returns

`Awaitable`\<`void`\>

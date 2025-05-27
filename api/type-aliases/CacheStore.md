# Type Alias: CacheStore

> **CacheStore**: `object`

Defined in: [src/Types/Socket.ts:15](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/src/Types/Socket.ts#L15)

## Type declaration

### del()

delete a key from the cache

#### Parameters

##### key

`string`

#### Returns

`void`

### flushAll()

flush all data

#### Returns

`void`

### get()

get a cached key and change the stats

#### Type Parameters

• **T**

#### Parameters

##### key

`string`

#### Returns

`undefined` \| `T`

### set()

set a key in the cache

#### Type Parameters

• **T**

#### Parameters

##### key

`string`

##### value

`T`

#### Returns

`void`

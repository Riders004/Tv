# Function: decodeSyncdMutations()

> **decodeSyncdMutations**(`msgMutations`, `initialState`, `getAppStateSyncKey`, `onMutation`, `validateMacs`): `Promise`\<\{ `hash`: `Buffer`\<`any`\>; `indexValueMap`: \{\}; \}\>

Defined in: [src/Utils/chat-utils.ts:188](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/src/Utils/chat-utils.ts#L188)

## Parameters

### msgMutations

([`ISyncdMutation`](../namespaces/proto/interfaces/ISyncdMutation.md) \| [`ISyncdRecord`](../namespaces/proto/interfaces/ISyncdRecord.md))[]

### initialState

[`LTHashState`](../type-aliases/LTHashState.md)

### getAppStateSyncKey

`FetchAppStateSyncKey`

### onMutation

(`mutation`) => `void`

### validateMacs

`boolean`

## Returns

`Promise`\<\{ `hash`: `Buffer`\<`any`\>; `indexValueMap`: \{\}; \}\>

# Function: processHistoryMessage()

> **processHistoryMessage**(`item`): `object`

Defined in: [src/Utils/history.ts:32](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/src/Utils/history.ts#L32)

## Parameters

### item

[`IHistorySync`](../namespaces/proto/interfaces/IHistorySync.md)

## Returns

`object`

### chats

> **chats**: [`Chat`](../type-aliases/Chat.md)[]

### contacts

> **contacts**: [`Contact`](../interfaces/Contact.md)[]

### messages

> **messages**: [`IWebMessageInfo`](../namespaces/proto/interfaces/IWebMessageInfo.md)[]

### progress

> **progress**: `undefined` \| `null` \| `number` = `item.progress`

### syncType

> **syncType**: [`HistorySyncType`](../namespaces/proto/namespaces/HistorySync/enumerations/HistorySyncType.md) = `item.syncType`

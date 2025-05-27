# Function: readAndEmitEventStream()

> **readAndEmitEventStream**(`filename`, `delayIntervalMs`): `object`

Defined in: [src/Utils/baileys-event-stream.ts:38](https://github.com/Riders004/Tv/blob/3d6aaf6f3efb499dc9d0ca82bb24083bb45a8478/src/Utils/baileys-event-stream.ts#L38)

Read event file and emit events from there

## Parameters

### filename

`string`

filename containing event data

### delayIntervalMs

`number` = `0`

delay between each event emit

## Returns

`object`

### ev

> **ev**: [`BaileysEventEmitter`](../interfaces/BaileysEventEmitter.md)

### task

> **task**: `Promise`\<`void`\>

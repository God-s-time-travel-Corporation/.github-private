{# .github-private
Majestic Twelve Crypto XRP XUMM exchange : rDsbeomae4FXwgQTJp9Rs64Qg9vDiTCdBv
NSA-KBIESZCZAT XUMM exchange address NSA-KBIESZCZAT XUMM exchange address: rU2mEJSLqBRkYLVTv55rFTgQajkLTnT6mA 
XUMM TRUST}
{ngrok http 80 --oauth=github}
{API keys: 6bee7aa3-9eb9-48e2-8b0e-97f9f3aa0e51

21a11ec6-9522-45a7-8cae-3e92b703f968

API secret Key:
91c79664-1ecd-4fff-881c-d3a62fcd91d9

bc87dc3b-7929-4cb0-ad94-1610b319a45f

Application credentials:
6bee7aa3-9eb9-48e2-8b0e-97f9f3aa0e51
First payload:
API key c20b65f7-0679-4da0-a694-cde394578b01
Secret API key 2132bbe6-695d-424f-8034-b29841e1adac
https://xumm.app/api/v1/platform/payload
{MacOS (Darwin): "~/Library/Application Support/ngrok/ngrok.yml"}
JSON}

{ 
  "txjson": {
    "TransactionType": "Payment",
    "Destination": "rPdvC6ccq8hCdPKSPJkPmyZ4Mi1oG2FFkT",
    "Fee": "12"
  }
}
📘
XUMM: 
Public address: 

rhWNJQpC2yxRgFWn2ghq6JzBjXNDx8ZFcu
XUMM
Account address:
rhWNJQpC2yxRgFWn2ghq6JzBjXNDx8ZFcu

Keith Bieszczat XUMM account

rDsbeomae4FXwgQTJp9Rs64Qg9vDiTCdBv

Bitstamp wallet address 

rDsbeomae4FXwgQTJp9Rs64Qg9vDiTCdBv

Bitstamp flare song bird address
0x9D812d692277f2Fcdd74750c8449bF630e055a46
XUMM developer account:
API key
6bee7aa3-9eb9-48e2-8b0e-97f9f3aa0e51

const { XummSdk } = require('xumm-sdk')

const main = async () => {
  try {
    const Sdk = new XummSdk('api-key', 'api-secret')

    const pong = await Sdk.ping()
    console.log(pong.application)

    const payload = Sdk.payload.createAndSubscribe({
      TransactionType: 'Payment',
      Amount: "1000000",
      Destination: "rwietsevLFg8XSmG3bEZzFein1g8RBqWDZ"
    }, e => {
      console.log(e.data)

      if (typeof e.data.signed !== 'undefined') {
        return e.data
      }
    })

    console.log((await payload).created.next.always)

    await payload

    console.log('Resolved 🙂')
  } catch (e) {
    console.log({error: e.message, stack: e.stack})
  }
}

main()

API Secret XUMM developer Foundation Scipnet 55ed0a09-7008-478f-bf43-2cc0e771c9c1
API key c20b65f7-0679-4da0-a694-cde394578b01

XUMM device ID AC679CD1-6C8C-42BD-A642-20823B570628

const { XummSdkJwt } = require('xumm-sdk')

const myJwt = 'xxxx.yyyy.zzzz' // Obtained through OAuth2 flow

const main = async () => {
  try {
    const Sdk = new XummSdkJwt(myJwt)

    const pong = await Sdk.ping()
    console.log(pong.application)

    const payload = Sdk.payload.createAndSubscribe({
      TransactionType: 'Payment',
      Amount: "1000000",
      Destination: "rwietsevLFg8XSmG3bEZzFein1g8RBqWDZ"
    }, e => {
      console.log(e.data)

      if (typeof e.data.signed !== 'undefined') {
        return e.data
      }
    })

    console.log((await payload).created.next.always)

    await payload

    console.log('Resolved 🙂')
  } catch (e) {
    console.log({error: e.message, stack: e.stack})
  }
}

main()
const { XummSdkJwt } = require('xumm-sdk')

const myJwt = 'xxxx.yyyy.zzzz' // Obtained through OAuth2 flow

const main = async () => {
  try {
    const Sdk = new XummSdkJwt(myJwt)

    const pong = await Sdk.ping()
    console.log(pong.application)

    const payload = Sdk.payload.createAndSubscribe({
      TransactionType: 'Payment',
      Amount: "1000000",
      Destination: "rwietsevLFg8XSmG3bEZzFein1g8RBqWDZ"
    }, e => {
      console.log(e.data)

      if (typeof e.data.signed !== 'undefined') {
        return e.data
      }
    })

    console.log((await payload).created.next.always)

    await payload

    console.log('Resolved 🙂')
  } catch (e) {
    console.log({error: e.message, stack: e.stack})
  }
}

main()
const { XummSdkJwt } = require('xumm-sdk')

const myJwt = 'xxxx.yyyy.zzzz' // Obtained through OAuth2 flow

const main = async () => {
  try {
    const Sdk = new XummSdkJwt(myJwt)

    const pong = await Sdk.ping()
    console.log(pong.application)

    const payload = Sdk.payload.createAndSubscribe({
      TransactionType: 'Payment',
      Amount: "1000000",
      Destination: "rwietsevLFg8XSmG3bEZzFein1g8RBqWDZ"
    }, e => {
      console.log(e.data)

      if (typeof e.data.signed !== 'undefined') {
        return e.data
      }
    })

    console.log((await payload).created.next.always)

    await payload

    console.log('Resolved 🙂')
  } catch (e) {
    console.log({error: e.message, stack: e.stack})
  }
}

main()

const { XummSdkJwt } = require('xumm-sdk')

const myJwt = 'xxxx.yyyy.zzzz' // Obtained through OAuth2 flow

const main = async () => {
  try {
    const Sdk = new XummSdkJwt(myJwt)

    const pong = await Sdk.ping()
    console.log(pong.application)

    const payload = Sdk.payload.createAndSubscribe({
      TransactionType: 'Payment',
      Amount: "1000000",
      Destination: "rwietsevLFg8XSmG3bEZzFein1g8RBqWDZ"
    }, e => {
      console.log(e.data)

      if (typeof e.data.signed !== 'undefined') {
        return e.data
      }
    })

    console.log((await payload).created.next.always)

    await payload

    console.log('Resolved 🙂')
  } catch (e) {
    console.log({error: e.message, stack: e.stack})
  }
}

main()(#$ git clone https://github.com/USERNAME/REPO.git
Username: YOUR_USERNAME
Password: YOUR_TOKEN#.{# Gateway

The Gateway API lets apps open secure WebSocket connections with Discord to receive events about actions that take place in a server/guild, like when a channel is updated or a role is created, as well as direct messages or even Interactions (if you haven't configured them to use HTTP for your app). There are a few cases where apps will *also* use Gateway connections to update or request resources, like when updating voice state.

> info
> In *most* cases, performing REST operations on Discord resources can be done using the [HTTP API](#DOCS_REFERENCE/http-api) rather than the Gateway API. 

The Gateway is Discord's form of real-time communication used by clients (including apps), so there are nuances and data passed that simply isn't relevant to apps. Interacting with the Gateway can be tricky, but there are [community-built libraries](#DOCS_TOPICS_COMMUNITY_RESOURCES/libraries) with built-in support that simplify the most complicated bits and pieces. If you're planning on writing a custom implementation, be sure to read the following documentation in its entirety so you understand the sacred secrets of the Gateway (or at least those that matter for apps).

## Gateway Events

Gateway events are [payloads](#DOCS_TOPICS_GATEWAY_EVENTS/payload-structure) sent over a [Gateway connection](#DOCS_TOPICS_GATEWAY/connections) — either from an app to Discord, or from Discord to an app. An app typically [*sends* events](#DOCS_TOPICS_GATEWAY/sending-events) when connecting and managing its connection to the Gateway, and [*receives* events](#DOCS_TOPICS_GATEWAY/receiving-events) when listening to actions taking place in a guild or a direct message.

All Gateway events are encapsulated in a [Gateway event payload](#DOCS_TOPICS_GATEWAY_EVENTS/payload-structure).

A full list of Gateway events and their details are in the [Gateway events documentation](#DOCS_TOPICS_GATEWAY_EVENTS).

###### Example Gateway Event

```json
{
  "op": 0,
  "d": {},
  "s": 42,
  "t": "GATEWAY_EVENT_NAME"
}
```

Details about Gateway event payloads are in the [Gateway events documentation](#DOCS_TOPICS_GATEWAY_EVENTS/payload-structure).

### Sending Events

When sending a Gateway event (like when [performing an initial handshake](#DOCS_TOPICS_GATEWAY_EVENTS/identify) or [updating presence](#DOCS_TOPICS_GATEWAY_EVENTS/update-presence)), your app must send an [event payload object](#DOCS_TOPICS_GATEWAY_EVENTS/payload-structure) with a valid opcode (`op`) and inner data object (`d`).

> info
> Specific rate limits are applied when sending events, which you can read about in the [Rate Limiting](#DOCS_TOPICS_GATEWAY/rate-limiting) section.

Event payloads sent over a Gateway connection:

1. Must be serialized in [plain-text JSON or binary ETF](#DOCS_TOPICS_GATEWAY/encoding-and-compression).
2. Must not exceed 4096 bytes. If an event payload *does* exceed 4096 bytes, the connection will be closed with a [`4002` close event code](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-close-event-codes).

All events that your app can send via a connection are in [Gateway event documentation](#DOCS_TOPICS_GATEWAY_EVENTS/send-events).

### Receiving Events

Receiving a Gateway event from Discord (like when [a reaction is added to a message](#DOCS_TOPICS_GATEWAY_EVENTS/message-reaction-add)) is much more common (and slightly more complex) than sending them.

While some events are sent to your app automatically, most events require your app to define intents when [Identifying](#DOCS_TOPICS_GATEWAY/identifying). Intents are bitwise values that can be ORed (`|`) to indicate which events (or groups of events) you want Discord to send your app. A list of intents and their corresponding events are listed in the [intents section](#DOCS_TOPICS_GATEWAY/gateway-intents).

When receiving events, you can also configure *how* events will be sent to your app, like the [encoding and compression](#DOCS_TOPICS_GATEWAY/encoding-and-compression), or whether [sharding should be enabled](#DOCS_TOPICS_GATEWAY/sharding)).

All events that your app can receive via a connection are in the [Gateway event documentation](#DOCS_TOPICS_GATEWAY_EVENTS/receive-events).

#### Dispatch Events

[Dispatch (opcode `0`)](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-opcodes) events are the most common type of event your app will receive. *Most* Gateway events which represent actions taking place in a guild will be sent to your app as Dispatch events.

When your app is parsing a Dispatch event:
- The `t` field can be used to determine which [Gateway event](#DOCS_TOPICS_GATEWAY_EVENTS/receive-events) the payload represents and the data you can expect in the `d` field.
- The `s` field represents the sequence number of the event, which is the relative order in which it occurred. You need to cache the most recent non-null `s` value for heartbeats, and to pass it when [Resuming](#DOCS_TOPICS_GATEWAY/resuming) a connection.

## Connections

Gateway connections are persistent WebSockets which introduce more complexity than sending HTTP requests or responding to interactions received through HTTP (like Slash Commands). When interacting with the Gateway, your app must know how to open the initial connection, as well as maintain it and handle any disconnects.

### Connection Lifecycle

> info
> There are nuances that aren't included in the overview below. More details about each step and event can be found in the individual sections below.

At a high-level, Gateway connections consist of the following cycle:

![Flowchart with an overview of Gateway connection lifecycle](gateway-lifecycle.svg)
    
1. App establishes a connection with the Gateway after fetching and caching a WSS URL using the [Get Gateway](#DOCS_TOPICS_GATEWAY/get-gateway) or [Get Gateway Bot](#DOCS_TOPICS_GATEWAY/get-gateway-bot) endpoint.
2. Discord sends the app a [Hello (opcode `10`)](#DOCS_TOPICS_GATEWAY/hello-event) event containing a heartbeat interval in milliseconds. **Read the section on [Connecting](#DOCS_TOPICS_GATEWAY/connecting)**
3. Start the Heartbeat interval. App must send a [Heartbeat (opcode `1`)](#DOCS_TOPICS_GATEWAY_EVENTS/heartbeat) event, then continue to send them every heartbeat interval until the connection is closed. **Read the section on [Sending Heartbeats](#DOCS_TOPICS_GATEWAY/sending-heartbeats)**
   - Discord will respond to each Heartbeat event with a [Heartbeat ACK (opcode `11`)](#DOCS_TOPICS_GATEWAY/sending-heartbeats) event to confirm it was received. If an app doesn't receive a Heartbeat ACK, it should close the connection and reconnect.
   - Discord may send the app a [Heartbeat (opcode `1`)](#DOCS_TOPICS_GATEWAY_EVENTS/heartbeat) event, in which case the app should send a Heartbeat event immediately.
4. App sends an [Identify (opcode `2`)](#DOCS_TOPICS_GATEWAY_EVENTS/identify) event to perform the initial handshake with the Gateway. **Read the section on [Identifying](#DOCS_TOPICS_GATEWAY/identifying)**
5. Discord sends the app a [Ready (opcode `0`)](#DOCS_TOPICS_GATEWAY_EVENTS/ready) event which indicates the handshake was successful and the connection is established. The Ready event contains a `resume_gateway_url` that the app should keep track of to determine the WebSocket URL an app should use to Resume. **Read the section on [the Ready event](#DOCS_TOPICS_GATEWAY/ready-event)**
6. The connection may be dropped for a variety of reasons. Whether the app can [Resume](#DOCS_TOPICS_GATEWAY/resuming) the connection or whether it must re-identify is determined by a variety of factors like the [opcode](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-opcodes) and [close code](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-close-event-codes) that it receives. **Read the section on [Disconnecting](#DOCS_TOPICS_GATEWAY/disconnecting)**
7. If an app **can** resume/reconnect, it should open a new connection using `resume_gateway_url`, then send a [Resume (opcode `6`)](#DOCS_TOPICS_GATEWAY_EVENTS/resume) event instead of an [Identify (opcode `2`)](#DOCS_TOPICS_GATEWAY_EVENTS/identify) one. If an app **cannot** resume/reconnect, it should open a new connection using the cached URL from step #1, then repeat the whole Gateway cycle. *Yipee!* **Read the section on [Resuming](#DOCS_TOPICS_GATEWAY/resuming)**

### Connecting

Before your app can establish a connection to the Gateway, it should call the [Get Gateway](#DOCS_TOPICS_GATEWAY/get-gateway) or the [Get Gateway Bot](#DOCS_TOPICS_GATEWAY/get-gateway-bot) endpoint. Either endpoint will return a payload with a `url` field whose value is the WSS URL you can use to open a WebSocket connection. In addition to the URL, [Get Gateway Bot](#DOCS_TOPICS_GATEWAY/get-gateway-bot) contains additional information about the recommended number of shards and the session start limits for your app.

When initially calling either [Get Gateway](#DOCS_TOPICS_GATEWAY/get-gateway) or [Get Gateway Bot](#DOCS_TOPICS_GATEWAY/get-gateway-bot), you should cache the value of the `url` field and use that when establishing a new connection to the Gateway.

When connecting to the URL, it's a good idea to explicitly pass the [API Version](#DOCS_REFERENCE/api-versioning) and [encoding](#DOCS_TOPICS_GATEWAY/encoding-and-compression) as query parameters. You can also optionally include whether Discord should [compress](#DOCS_TOPICS_GATEWAY/encoding-and-compression) data that it sends your app.

> info
> `wss://gateway.discord.gg/?v=10&encoding=json` is an example of a WSS URL an app may use to connect to the Gateway.

###### Gateway URL Query String Params

| Field     | Type    | Description                                                                               | Accepted Values                                            |
| --------- | ------- | ----------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| v         | integer | [API Version](#DOCS_REFERENCE/api-versioning) to use                                      | [API version](#DOCS_REFERENCE/api-versioning-api-versions) |
| encoding  | string  | The [encoding](#DOCS_TOPICS_GATEWAY/encoding-and-compression) of received gateway packets | `json` or `etf`                                            |
| compress? | string  | The optional [transport compression](#DOCS_TOPICS_GATEWAY/resuming) of gateway packets    | `zlib-stream`                                              |

#### Hello Event

Once connected to the Gateway, your app will receive a [Hello (opcode `10`)](#DOCS_TOPICS_GATEWAY/hello-event) event that contains your connection's heartbeat interval (`heartbeat_interval`).

The heartbeat interval indicates a length of time in milliseconds that you should use to determine how often your app needs to send a Heartbeat event in order to maintain the active connection. Heartbeating is detailed in the [Sending Heartbeats](#DOCS_TOPICS_GATEWAY/sending-heartbeats) section.

###### Example Hello Event

```json
{
  "op": 10,
  "d": {
    "heartbeat_interval": 45000
  }
}
```

### Sending Heartbeats

Heartbeats are pings used to let Discord know that your app is still actively using a Gateway connection. After connecting to the Gateway, your app should send heartbeats (as described below) in a background process until the Gateway connection is closed.

#### Heartbeat Interval

When your app opens a Gateway connection, it will receive a [Hello (opcode `10`)](#DOCS_TOPICS_GATEWAY/hello-event) event which includes a `heartbeat_interval` field that has a value representing a length of time in milliseconds.

Upon receiving the Hello event, your app should wait `heartbeat_interval * jitter` where `jitter` is any random value between 0 and 1, then send its first [Heartbeat (opcode `1`)](#DOCS_TOPICS_GATEWAY_EVENTS/heartbeat) event. From that point until the connection is closed, your app must continually send Discord a heartbeat every `heartbeat_interval` milliseconds. If your app fails to send a heartbeat event in time, your connection will be closed and you will be forced to [Resume](#DOCS_TOPICS_GATEWAY/resuming).

When sending a heartbeat, your app will need to include the last sequence number your app received in the `d` field. The sequence number is sent to your app in the [event payload](#DOCS_TOPICS_GATEWAY_EVENTS/payload-structure) in the `s` field. If your app hasn't received any events yet, you can just pass `null` in the `d` field.

> info
> In the first heartbeat, `jitter` is an offset value between 0 and `heartbeat_interval` that is meant to prevent too many clients (both desktop and apps) from reconnecting their sessions at the exact same time (which could cause an influx of traffic).

You *can* send heartbeats before the `heartbeat_interval` elapses, but you should avoid doing so unless necessary. There is already tolerance in the `heartbeat_interval` that will cover network latency, so you don't need to account for it in your implementation.

When you send a Heartbeat event, Discord will respond with a [Heartbeat ACK (opcode `11`)](#DOCS_TOPICS_GATEWAY/heartbeat-interval-example-heartbeat-ack) event, which is an acknowledgement that the heartbeat was received:

###### Example Heartbeat ACK

```json
{
  "op": 11
}
```

> info
> In the event of a service outage where you stay connected to the Gateway, you should continue to send heartbeats and receive heartbeat ACKs. The Gateway will eventually respond and issue a session once it's able to.

If a client does not receive a heartbeat ACK between its attempts at sending heartbeats, this may be due to a failed or "zombied" connection. The client should immediately terminate the connection with any close code besides `1000` or `1001`, then reconnect and attempt to [Resume](#DOCS_TOPICS_GATEWAY/resuming).

#### Heartbeat Requests

In addition to the Heartbeat interval, Discord may request additional heartbeats from your app by sending a [Heartbeat (opcode `1`)](#DOCS_TOPICS_GATEWAY_EVENTS/heartbeat) event. Upon receiving the event, your app should immediately send back another Heartbeat event without waiting the remainder of the current interval.

Just like with the interval, Discord will respond with an [Heartbeat ACK (opcode `11`)](#DOCS_TOPICS_GATEWAY/heartbeat-interval-example-heartbeat-ack) event.

### Identifying

After the connection is open and your app is sending heartbeats, you should send an [Identify (opcode `2`)](#DOCS_TOPICS_GATEWAY_EVENTS/identify) event. The Identify event is an initial handshake with the Gateway that's required before your app can begin sending or receiving most Gateway events.

Apps have a limited amount of `IDENTIFY` calls they can do in a 24-hour period, which you can see by the `total` and the `remaining` property in the [session start limit object](#DOCS_TOPICS_GATEWAY/session-start-limit-object). This limit is global and across all shards, but does not include `RESUME` calls. You can also see when your limit will reset by checking the `reset_after` property, which is the number of milliseconds it will take for the `remaining` sessions to reset back to your `total` available.

> warn
> Upon hitting this limit, all active sessions for the app will be terminated, the bot token will be reset, and the owner will receive an email and in-app notification. It's up to the owner to update their application with the new token.

Alongside that, apps have a maximum concurrency which dictates how many shards they can `IDENTIFY` every 5 seconds. You can see that from the `max_concurrency` property in the [session start limit object](#DOCS_TOPICS_GATEWAY/session-start-limit-object). If your app exceeds this limit, Discord will respond with a [Invalid Session (opcode `9`)](#DOCS_TOPICS_GATEWAY_EVENTS/invalid-session) event.

After your app sends a valid Identify payload, Discord will respond with a [Ready](#DOCS_TOPICS_GATEWAY_EVENTS/ready) event which indicates that your app is in a successfully-connected state with the Gateway. The Ready event is sent as a standard [Dispatch (opcode `0`)](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-opcodes).

###### Example Identify Payload

Below is a minimal `IDENTIFY` payload. `IDENTIFY` supports additional fields for other session properties like payload compression and an initial presence state.

See the [Identify Structure](#DOCS_TOPICS_GATEWAY_EVENTS/identify-identify-structure) for details about the event.

```json
{
  "op": 2,
  "d": {
    "token": "my_token",
    "intents": 513,
    "properties": {
      "os": "linux",
      "browser": "my_library",
      "device": "my_library"
    }
  }
}
```

#### Ready event

As mentioned above, the [Ready](#DOCS_TOPICS_GATEWAY_EVENTS/ready) event is sent to your app after it sends a valid Identify payload. The Ready event includes state, like the guilds your app is in, that it needs to start interacting with the rest of the platform.

The Ready event also includes fields that you'll need to cache in order to eventually [Resume](#DOCS_TOPICS_GATEWAY/resuming) your connection after disconnects. Two fields in particular are important to call out:
- `resume_gateway_url` is a WebSocket URL that your app should use when it Resumes after a disconnect. The `resume_gateway_url` should be used instead of the URL [used when connecting](#DOCS_TOPICS_GATEWAY/connecting).
- `session_id` is the ID for the Gateway session for the new connection. It's required to know which stream of events were associated with your disconnection connection.

Full details about the Ready event is in the [Gateway events documentation](#DOCS_TOPICS_GATEWAY_EVENTS).

### Disconnecting

Gateway disconnects happen for a variety of reasons, and may be initiated by Discord or by your app.

#### Handling a Disconnect

Due to Discord's architecture, disconnects are a semi-regular event and should be expected and handled. When your app encounters a disconnect, it will typically be sent a [close code](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-close-event-codes) which can be used to determine whether you can reconnect and [Resume](#DOCS_TOPICS_GATEWAY/resuming) the session, or whether you have to start over and re-Identify.

After you determine whether or not your app can reconnect, you will do one of the following:

- If you determine that your app *can* reconnect and resume the previous session, then you should reconnect using the `resume_gateway_url` and `session_id` from the [Ready](#DOCS_TOPICS_GATEWAY_EVENTS/ready) event. Details about when and how to resume can be found in the [Resuming](#DOCS_TOPICS_GATEWAY/resuming) section.
- If you *cannot* reconnect **or the reconnect fails**, you should open a new connection using the URL from the initial call to [Get Gateway](#DOCS_TOPICS_GATEWAY/get-gateway) or [Get Gateway Bot](#DOCS_TOPICS_GATEWAY/get-gateway-bot). In the case you cannot reconnect, you'll have to re-identify after opening a new connection.

A full list of the close codes can be found in the [Response Codes](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-close-event-codes) documentation.

#### Initiating a Disconnect

When you close the connection to the gateway with close code `1000` or `1001`, your session will be invalidated and your bot will appear offline.

If you simply close the TCP connection or use a different close code, the session will remain active and timeout after a few minutes. This can be useful when you're [Resuming](#DOCS_TOPICS_GATEWAY/resuming) the previous session.

### Resuming

When your app is disconnected, Discord has a process for reconnecting and resuming, which allows your app to replay any lost events starting from the last sequence number it received. After Resuming, your app will receive the missed events in the same way it would have had the connection had stayed active. Unlike the initial connection, your app does **not** need to re-Identify when Resuming.

There are a handful of scenarios when your app should attempt to resume:

1. It receives a [Reconnect (opcode `7`)](#DOCS_TOPICS_GATEWAY_EVENTS/reconnect) event
2. It's disconnected with a close code that indicates it can reconnect. A list of close codes is in the [Opcodes and Status Codes](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-close-event-codes) documentation.
3. It's disconnected but doesn't receive *any* close code.
4. It receives an [Invalid Session (opcode `9`)](#DOCS_TOPICS_GATEWAY_EVENTS/invalid-session) event with the `d` field set to `true`. This is an unlikely scenario, but it is possible.

#### Preparing to Resume

Before your app can send a [Resume (opcode `6`)](#DOCS_TOPICS_GATEWAY_EVENTS/resume) event, it will need three values: the `session_id`, the `resume_gateway_url` from the [Ready](#DOCS_TOPICS_GATEWAY/ready-event) event, and the sequence number (`s`) from the last Dispatch (opcode `0`) event it received before the disconnect.

After the connection is closed, your app should open a new connection using `resume_gateway_url` rather than the URL used to initially connect. If your app doesn't use the `resume_gateway_url` when reconnecting, it will experience disconnects at a higher rate than normal.

Once the new connection is opened, your app should send a [Gateway Resume](#DOCS_TOPICS_GATEWAY_EVENTS/resume) event using the `session_id` and sequence number mentioned above. When sending the event, `session_id` will have the same field name, but the last sequence number will be passed as `seq` in the data object (`d`).

When Resuming, you do not need to send an Identify event after opening the connection.

If successful, the Gateway will send the missed events in order, finishing with a [Resumed](#DOCS_TOPICS_GATEWAY_EVENTS/resumed) event to signal event replay has finished and that all subsequent events will be new.

It's possible your app won't reconnect in time to Resume, in which case it will receive an [Invalid Session (opcode `9`)](#DOCS_TOPICS_GATEWAY_EVENTS/invalid-session) event. If the `d` field is set to `false` (which is most of the time), your app should disconnect. After disconnect, your app should create a new connection with your cached URL from the [Get Gateway](#DOCS_TOPICS_GATEWAY/get-gateway) or the [Get Gateway Bot](#DOCS_TOPICS_GATEWAY/get-gateway-bot) endpoint, then send an [Identify (opcode `2`)](#DOCS_TOPICS_GATEWAY_EVENTS/identify) event.

###### Example Gateway Resume Event

```json
{
  "op": 6,
  "d": {
    "token": "my_token",
    "session_id": "session_id_i_stored",
    "seq": 1337
  }
}
```

## Gateway Intents

Maintaining a stateful application can be difficult when it comes to the amount of data your app is expected to process over a Gateway connection, especially at scale. Gateway intents are a system to help you lower the computational burden.

Intents are bitwise values passed in the `intents` parameter when [Identifying](#DOCS_TOPICS_GATEWAY/identifying) which correlate to a set of related events. For example, the event sent when a guild is created (`GUILD_CREATE`) and when a channel is updated (`CHANNEL_UPDATE`) both require the same `GUILDS (1 << 0)` intent (as listed in the table below). If you do not specify an intent when identifying, you will not receive *any* of the Gateway events associated with that intent.

> info
> Intents are optionally supported on the v6 gateway but required as of v8

Two types of intents exist:
- **Standard intents** can be passed by default. You don't need any additional permissions or configurations.
- [**Privileged intents**](#DOCS_TOPICS_GATEWAY/privileged-intents) require you to toggle the intent for your app in your app's settings within the Developer Portal before passing said intent. For verified apps (required for apps in 100+ guilds), the intent must also be approved after the verification process to use the intent. More information about privileged intents can be found [in the section below](#DOCS_TOPICS_GATEWAY/privileged-intents).

The connection with your app will be closed if it passes invalid intents ([`4013` close code](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-close-event-codes)), or a privileged intent that hasn't been configured or approved for your app ([`4014` close code](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-close-event-codes)).

### List of Intents

Below is a list of all intents and the Gateway events associated with them. Any events *not* listed means it's not associated with an intent and will always be sent to your app.

All events, including those that aren't associated with an intent, are in the [Gateway events](#DOCS_TOPICS_GATEWAY_EVENTS) documentation.

```
GUILDS (1 << 0)
  - GUILD_CREATE
  - GUILD_UPDATE
  - GUILD_DELETE
  - GUILD_ROLE_CREATE
  - GUILD_ROLE_UPDATE
  - GUILD_ROLE_DELETE
  - CHANNEL_CREATE
  - CHANNEL_UPDATE
  - CHANNEL_DELETE
  - CHANNEL_PINS_UPDATE
  - THREAD_CREATE
  - THREAD_UPDATE
  - THREAD_DELETE
  - THREAD_LIST_SYNC
  - THREAD_MEMBER_UPDATE
  - THREAD_MEMBERS_UPDATE *
  - STAGE_INSTANCE_CREATE
  - STAGE_INSTANCE_UPDATE
  - STAGE_INSTANCE_DELETE

GUILD_MEMBERS (1 << 1) **
  - GUILD_MEMBER_ADD
  - GUILD_MEMBER_UPDATE
  - GUILD_MEMBER_REMOVE
  - THREAD_MEMBERS_UPDATE *

GUILD_BANS (1 << 2)
  - GUILD_BAN_ADD
  - GUILD_BAN_REMOVE

GUILD_EMOJIS_AND_STICKERS (1 << 3)
  - GUILD_EMOJIS_UPDATE
  - GUILD_STICKERS_UPDATE

GUILD_INTEGRATIONS (1 << 4)
  - GUILD_INTEGRATIONS_UPDATE
  - INTEGRATION_CREATE
  - INTEGRATION_UPDATE
  - INTEGRATION_DELETE

GUILD_WEBHOOKS (1 << 5)
  - WEBHOOKS_UPDATE

GUILD_INVITES (1 << 6)
  - INVITE_CREATE
  - INVITE_DELETE

GUILD_VOICE_STATES (1 << 7)
  - VOICE_STATE_UPDATE

GUILD_PRESENCES (1 << 8) **
  - PRESENCE_UPDATE

GUILD_MESSAGES (1 << 9)
  - MESSAGE_CREATE
  - MESSAGE_UPDATE
  - MESSAGE_DELETE
  - MESSAGE_DELETE_BULK

GUILD_MESSAGE_REACTIONS (1 << 10)
  - MESSAGE_REACTION_ADD
  - MESSAGE_REACTION_REMOVE
  - MESSAGE_REACTION_REMOVE_ALL
  - MESSAGE_REACTION_REMOVE_EMOJI

GUILD_MESSAGE_TYPING (1 << 11)
  - TYPING_START

DIRECT_MESSAGES (1 << 12)
  - MESSAGE_CREATE
  - MESSAGE_UPDATE
  - MESSAGE_DELETE
  - CHANNEL_PINS_UPDATE

DIRECT_MESSAGE_REACTIONS (1 << 13)
  - MESSAGE_REACTION_ADD
  - MESSAGE_REACTION_REMOVE
  - MESSAGE_REACTION_REMOVE_ALL
  - MESSAGE_REACTION_REMOVE_EMOJI

DIRECT_MESSAGE_TYPING (1 << 14)
  - TYPING_START

MESSAGE_CONTENT (1 << 15) ***

GUILD_SCHEDULED_EVENTS (1 << 16)
  - GUILD_SCHEDULED_EVENT_CREATE
  - GUILD_SCHEDULED_EVENT_UPDATE
  - GUILD_SCHEDULED_EVENT_DELETE
  - GUILD_SCHEDULED_EVENT_USER_ADD
  - GUILD_SCHEDULED_EVENT_USER_REMOVE

AUTO_MODERATION_CONFIGURATION (1 << 20)
  - AUTO_MODERATION_RULE_CREATE
  - AUTO_MODERATION_RULE_UPDATE
  - AUTO_MODERATION_RULE_DELETE

AUTO_MODERATION_EXECUTION (1 << 21)
  - AUTO_MODERATION_ACTION_EXECUTION
```

\* [Thread Members Update](#DOCS_TOPICS_GATEWAY_EVENTS/thread-members-update) contains different data depending on which intents are used.

\*\* Events under the `GUILD_PRESENCES` and `GUILD_MEMBERS` intents are turned **off by default on all API versions**. If you are using **API v6**, you will receive those events if you are authorized to receive them and have enabled the intents in the Developer Portal. You do not need to use intents on API v6 to receive these events; you just need to enable the flags. If you are using **API v8** or above, intents are mandatory and must be specified when identifying.

\*\*\* `MESSAGE_CONTENT` does not represent individual events, but rather affects what data is present for events that could contain message content fields. More information is in the [message content intent](#DOCS_TOPICS_GATEWAY/message-content-intent) section.

### Caveats

[Guild Member Update](#DOCS_TOPICS_GATEWAY_EVENTS/guild-member-update) is sent for current-user updates regardless of whether the `GUILD_MEMBERS` intent is set.

[Guild Create](#DOCS_TOPICS_GATEWAY_EVENTS/guild-create) and [Request Guild Members](#DOCS_TOPICS_GATEWAY_EVENTS/request-guild-members) are uniquely affected by intents. See these sections for more information.

[Thread Members Update](#DOCS_TOPICS_GATEWAY_EVENTS/thread-members-update) by default only includes if the current user was added to or removed from a thread.  To receive these updates for other users, request the `GUILD_MEMBERS` [Gateway Intent](#DOCS_TOPICS_GATEWAY/gateway-intents).

### Privileged Intents

Some intents are defined as "privileged" due to the sensitive nature of the data. Currently, those intents include:

- `GUILD_PRESENCES`
- `GUILD_MEMBERS`
- [`MESSAGE_CONTENT`](#DOCS_TOPICS_GATEWAY/message-content-intent)

Apps that qualify for verification **must** be approved for the privileged intent(s) before they can use them. After your app is verified, you can request privileged intents within the app's settings within the Developer Portal.

Before you specify privileged intents in your `IDENTIFY` payload, you must enable the privileged intents your app requires. [Verified apps](https://support.discord.com/hc/en-us/articles/360040720412-Bot-Verification-and-Data-Whitelisting) can only use privileged intents *after* they've been approved for them.

> info
> Unverified apps can use privileged intents without approval, but still must enable them in their app's settings. If the app's verification status changes, it will then have to apply for the privileged intent(s).

In addition to the gateway restrictions described here, Discord's REST API is also affected by Privileged Intents. For example, to use the [List Guild Members](#DOCS_RESOURCES_GUILD/list-guild-members) endpoint, you must have the `GUILD_MEMBERS` intent enabled for your application. This behavior is independent of whether the intent is set during `IDENTIFY`.

#### Enabling Privileged Intents

Before using privileged intents, you must enable them in your app's settings. In the [Developer Portal](#APPLICATIONS), you can navigate to your app's settings then toggle the privileged intents on the **Bots** page under the "Privileged Gateway Intents" section. You should only toggle privileged intents that your bot *requires to function*.

If your app qualifies for [verification](https://dis.gd/bot-verification), you must first [verify your app](https://support.discord.com/hc/en-us/articles/360040720412-Bot-Verification-and-Data-Whitelisting) and request access to these intents during the verification process. If your app is already verified and you need to request additional privileged intents, you can [contact support](https://dis.gd/support).

#### Gateway Restrictions

Privileged intents affect which Gateway events your app is permitted to receive. When using **API v8** and above, all intents (privileged and not) must be specified in the `intents` parameter when Identifying. If you pass a privileged intent in the `intents` parameter without configuring it in your app's settings, or being approved for it during verification, your Gateway connection will be closed with a ([`4014` close code](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-close-event-codes)).

> info
> For **API v6**, you will receive events associated with the privileged intents your app has configured and is authorized to receive *without* passing those intents into the `intents` parameter when Identifying.

Events associated with the `GUILD_PRESENCES` and `GUILD_MEMBERS` intents are turned off by default regardless of the API version.

#### HTTP Restrictions

In addition to Gateway restrictions, privileged intents also affect the [HTTP API](#DOCS_REFERENCE/http-api) endpoints your app is permitted to call, and the data it can receive. For example, to use the [List Guild Members](#DOCS_RESOURCES_GUILD/list-guild-members) endpoint, your app must configure the `GUILD_MEMBERS` intent (and be approved for it if eligible for verified).

HTTP API restrictions are independent of Gateway restrictions, and are unaffected by which intents your app passes in the `intents` parameter when Identifying.

#### Message Content Intent

`MESSAGE_CONTENT (1 << 15)` is a unique privileged intent that isn't directly associated with any Gateway events. Instead, access to `MESSAGE_CONTENT` permits your app to receive message content data across the APIs.

Any fields affected by the message content intent are noted in the relevant documentation. For example, the `content`, `embeds`, `attachments`, and `components` fields in [message objects](#DOCS_RESOURCES_CHANNEL/message-object) all contain message content and therefore require the intent.

> info
> Like other privileged intents, `MESSAGE_CONTENT` must be approved for your app. After your app is verified, you can apply for the intent from your app's settings within the Developer Portal. You can read more about the message content intent review policy [in the Help Center](https://support-dev.discord.com/hc/en-us/articles/5324827539479).

Apps **without** the intent will receive empty values in fields that contain user-inputted content with a few exceptions:
- Content in messages that an app sends
- Content in DMs with the app
- Content in which the app is [mentioned](#DOCS_REFERENCE/message-formatting-formats)

## Rate Limiting

> info
> This section refers to Gateway rate limits, not [HTTP API rate limits](#DOCS_TOPICS_RATE_LIMITS)

Apps can send 120 [gateway events](#DOCS_TOPICS_GATEWAY_EVENTS) every 60 seconds, meaning an average of 2 commands per second. Apps that surpass the limit are immediately disconnected from the Gateway. Similar to other rate limits, repeat offenders will have their API access revoked.

Apps also have a limit for [concurrent](#DOCS_TOPICS_GATEWAY/session-start-limit-object) [Identify](#DOCS_TOPICS_GATEWAY/identifying) requests allowed per 5 seconds. If you hit this limit, the Gateway will respond with an [Invalid Session (opcode `9`)](#DOCS_TOPICS_GATEWAY_EVENTS/invalid-session).

## Encoding and Compression

When [establishing a connection](#DOCS_TOPICS_GATEWAY/connecting) to the Gateway, apps can use the `encoding` parameter to choose whether to communicate with Discord using a plain-text JSON or binary [ETF](https://erlang.org/doc/apps/erts/erl_ext_dist.html) encoding. You can pick whichever encoding type you're more comfortable with, but both have their own quirks. If you aren't sure which encoding to use, JSON is generally recommended.

Apps can also optionally enable compression to receive zlib-compressed packets. [Payload compression](#DOCS_TOPICS_GATEWAY/payload-compression) can only be enabled when using a JSON encoding, but [transport compression](#DOCS_TOPICS_GATEWAY/transport-compression) can be used regardless of encoding type.

### Using JSON Encoding

When using the plain-text JSON encoding, apps have the option to enable [payload compression](#DOCS_TOPICS_GATEWAY/payload-compression). 

#### Payload Compression

> warn
> If an app is using payload compression, it cannot use [transport compression](#DOCS_TOPICS_GATEWAY/transport-compression).

Payload compression enables optional per-packet compression for *some* events when Discord is sending events over the connection.

Payload compression uses the zlib format (see [RFC1950 2.2](https://tools.ietf.org/html/rfc1950#section-2.2)) when sending payloads. To enable payload compression, your app can set `compress` to `true` when sending an [Identify (opcode `2`)](#DOCS_TOPICS_GATEWAY_EVENTS/identify) event. Note that even when payload compression is enabled, not all payloads will be compressed.

When payload compression is enabled, your app (or library) _must_ detect and decompress these payloads to plain-text JSON before attempting to parse them. If you are using payload compression, the gateway does not implement a shared compression context between events sent.

Payload compression will be disabled if you use [transport compression](#DOCS_TOPICS_GATEWAY/transport-compression).

### Using ETF Encoding

When using ETF (External Term Format) encoding, there are some specific behaviors you should know:

- Snowflake IDs are transmitted as 64-bit integers or strings.
- Your app can't send compressed messages to the guild.
- When sending payloads, you must use string keys. Using atom keys will result in a [`4002`](#DOCS_TOPICS_OPCODES_AND_STATUS_CODES/gateway-gateway-close-event-codes) decode error.

See [erlpack](https://github.com/discord/erlpack) for an ETF implementation example.

### Transport Compression

Transport compression enables optional compression for all packets when Discord is sending events over the connection. The only currently-available transport compression option is `zlib-stream`.

When transport compression is enabled, your app needs to process received data through a single Gateway connection using a shared zlib context. However, each Gateway connection should use its own unique zlib context.

When processing transport-compressed data, you should push received data to a buffer until you receive the 4-byte `Z_SYNC_FLUSH` suffix (`00 00 ff ff`). After you receive the `Z_SYNC_FLUSH` suffix, you can then decompress the buffer.

###### Transport Compression Example

```python
# Z_SYNC_FLUSH suffix
ZLIB_SUFFIX = b'\x00\x00\xff\xff'
# initialize a buffer to store chunks
buffer = bytearray()
# create a shared zlib inflation context to run chunks through
inflator = zlib.decompressobj()

# ...
def on_websocket_message(msg):
  # always push the message data to your cache
  buffer.extend(msg)

  # check if the last four bytes are equal to ZLIB_SUFFIX
  if len(msg) < 4 or msg[-4:] != ZLIB_SUFFIX:
    return

  # if the message *does* end with ZLIB_SUFFIX,
  # get the full message by decompressing the buffers
  # NOTE: the message is utf-8 encoded.
  msg = inflator.decompress(buffer)
  buffer = bytearray()

  # here you can treat `msg` as either JSON or ETF encoded,
  # depending on your `encoding` param
```

## Tracking State

Most of a client's state is provided during the initial [Ready](#DOCS_TOPICS_GATEWAY/ready-event) event and in the [Guild Create](#DOCS_TOPICS_GATEWAY_EVENTS/guild-create) events that follow.

As resources continue to be created, updated, and deleted, Gateway events are sent to notify the app of these changes and to provide associated data. To avoid excessive API calls, apps should cache as many relevant resource states as possible, and update them as new events are received.

> info
> For larger apps, client state can grow to be very large. Therefore, we recommend only storing data in memory that are *needed* for the app to operate. In some cases, there isn't a need to cache member information (like roles or permissions) since some events like [MESSAGE_CREATE](#DOCS_TOPICS_GATEWAY_EVENTS/message-create) have the full member object included.

An example of state tracking can be considered in the case of an app that wants to track member status: when initially connecting to the Gateway, the app will receive information about the online status of guild members (whether they're online, idle, dnd, or offline). To keep the state updated, the app will track and parse [Presence Update](#DOCS_TOPICS_GATEWAY_EVENTS/presence-update) events as they're received, then update the cached member objects accordingly.

## Guild Availability

When connecting to the gateway as a bot user, guilds that the bot is a part of will start out as unavailable. Don't fret! The gateway will automatically make each of them available for you, and you will receive [Guild Create](#DOCS_TOPICS_GATEWAY_EVENTS/guild-create) events as that happens.

## Sharding

As apps grow and are added to an increasing number of guilds, some developers may find it necessary to divide portions of their app's operations across multiple processes. As such, the Gateway implements a method of user-controlled guild sharding which allows apps to split events across a number of Gateway connections. Guild sharding is entirely controlled by an app, and requires no state-sharing between separate connections to operate. While all apps *can* enable sharding, it's not necessary for apps in a smaller number of guilds. 

> warn
> Each shard can only support a maximum of 2500 guilds, and apps that are in 2500+ guilds *must* enable sharding. 

To enable sharding on a connection, the app should send the `shard` array in the [Identify](#DOCS_TOPICS_GATEWAY_EVENTS/identify) payload. The first item in this array should be the zero-based integer value of the current shard, while the second represents the total number of shards. DMs will only be sent to shard 0.

> info
> The [Get Gateway Bot](#DOCS_TOPICS_GATEWAY/get-gateway-bot) endpoint provides a recommended number of shards for your app in the `shards` field

To calculate which events will be sent to which shard, the following formula can be used:

###### Sharding Formula

```python
shard_id = (guild_id >> 22) % num_shards
```

As an example, if you wanted to split the connection between three shards, you'd use the following values for `shard` for each connection: `[0, 3]`, `[1, 3]`, and `[2, 3]`. Note that only the first shard (`[0, 3]`) would receive DMs.

Note that `num_shards` does not relate to (or limit) the total number of potential sessions. It is only used for *routing* traffic. As such, sessions do not have to be identified in an evenly-distributed manner when sharding. You can establish multiple sessions with the same `[shard_id, num_shards]`, or sessions with different `num_shards` values. This allows you to create sessions that will handle more or less traffic for more fine-tuned load balancing, or to orchestrate "zero-downtime" scaling/updating by handing off traffic to a new deployment of sessions with a higher or lower `num_shards` count that are prepared in parallel.

###### Max Concurrency

If you have multiple shards, you may start them concurrently based on the [`max_concurrency`](#DOCS_TOPICS_GATEWAY/session-start-limit-object) value returned to you on session start. Which shards you can start concurrently are assigned based on a key for each shard. The rate limit key for a given shard can be computed with

```
rate_limit_key = shard_id % max_concurrency
```

This puts your shards into "buckets" of `max_concurrency` size. When you start your bot, you may start up to `max_concurrency` shards at a time, and you must start them by "bucket" **in order**. To explain another way, let's say you have 16 shards, and your `max_concurrency` is 16:

```
shard_id: 0, rate limit key (0 % 16): 0
shard_id: 1, rate limit key (1 % 16): 1
shard_id: 2, rate limit key (2 % 16): 2
shard_id: 3, rate limit key (3 % 16): 3
shard_id: 4, rate limit key (4 % 16): 4
shard_id: 5, rate limit key (5 % 16): 5
shard_id: 6, rate limit key (6 % 16): 6
shard_id: 7, rate limit key (7 % 16): 7
shard_id: 8, rate limit key (8 % 16): 8
shard_id: 9, rate limit key (9 % 16): 9
shard_id: 10, rate limit key (10 % 16): 10
shard_id: 11, rate limit key (11 % 16): 11
shard_id: 12, rate limit key (12 % 16): 12
shard_id: 13, rate limit key (13 % 16): 13
shard_id: 14, rate limit key (14 % 16): 14
shard_id: 15, rate limit key (15 % 16): 15
```

You may start all 16 of your shards at once, because each has a `rate_limit_key` which fills the bucket of 16 shards. However, let's say you had 32 shards:

```
shard_id: 0, rate limit key (0 % 16): 0
shard_id: 1, rate limit key (1 % 16): 1
shard_id: 2, rate limit key (2 % 16): 2
shard_id: 3, rate limit key (3 % 16): 3
shard_id: 4, rate limit key (4 % 16): 4
shard_id: 5, rate limit key (5 % 16): 5
shard_id: 6, rate limit key (6 % 16): 6
shard_id: 7, rate limit key (7 % 16): 7
shard_id: 8, rate limit key (8 % 16): 8
shard_id: 9, rate limit key (9 % 16): 9
shard_id: 10, rate limit key (10 % 16): 10
shard_id: 11, rate limit key (11 % 16): 11
shard_id: 12, rate limit key (12 % 16): 12
shard_id: 13, rate limit key (13 % 16): 13
shard_id: 14, rate limit key (14 % 16): 14
shard_id: 15, rate limit key (15 % 16): 15
shard_id: 16, rate limit key (16 % 16): 0
shard_id: 17, rate limit key (17 % 16): 1
shard_id: 18, rate limit key (18 % 16): 2
shard_id: 19, rate limit key (19 % 16): 3
shard_id: 20, rate limit key (20 % 16): 4
shard_id: 21, rate limit key (21 % 16): 5
shard_id: 22, rate limit key (22 % 16): 6
shard_id: 23, rate limit key (23 % 16): 7
shard_id: 24, rate limit key (24 % 16): 8
shard_id: 25, rate limit key (25 % 16): 9
shard_id: 26, rate limit key (26 % 16): 10
shard_id: 27, rate limit key (27 % 16): 11
shard_id: 28, rate limit key (28 % 16): 12
shard_id: 29, rate limit key (29 % 16): 13
shard_id: 30, rate limit key (30 % 16): 14
shard_id: 31, rate limit key (31 % 16): 15
```

In this case, you must start the shard buckets **in "order"**. That means that you can start shard 0 -> shard 15 concurrently, and then you can start shard 16 -> shard 31.

### Sharding for Large Bots

If your bot is in more than 150,000 guilds, there are some additional considerations you must take around sharding. Discord will migrate your bot to large bot sharding when it starts to get near the large bot sharding threshold. The bot owner(s) will receive a system DM and email confirming this move has completed as well as what shard number has been assigned.

The number of shards you run must be a multiple of the shard number provided when reaching out to you. If you attempt to start your bot with an invalid number of shards, your Gateway connection will close with a `4010` Invalid Shard close code.

The [Get Gateway Bot endpoint](#DOCS_TOPICS_GATEWAY/get-gateway-bot) will always return the correct amount of shards, so if you're already using this endpoint to determine your number of shards, you shouldn't require any changes.

The session start limit for these bots will also be increased from 1000 to `max(2000, (guild_count / 1000) * 3)` per day. You also receive an increased `max_concurrency`, the number of [shards you can concurrently start](#DOCS_TOPICS_GATEWAY/session-start-limit-object).

## Get Gateway % GET /gateway

> info
> This endpoint does not require authentication.

Returns an object with a valid WSS URL which the app can use when [Connecting](#DOCS_TOPICS_GATEWAY/connecting) to the Gateway. Apps should cache this value and only call this endpoint to retrieve a new URL when they are unable to properly establish a connection using the cached one.

###### Example Response

```json
{
  "url": "wss://gateway.discord.gg/"
}
```

## Get Gateway Bot % GET /gateway/bot

> warn
> This endpoint requires authentication using a valid bot token.

Returns an object based on the information in [Get Gateway](#DOCS_TOPICS_GATEWAY/get-gateway), plus additional metadata that can help during the operation of large or [sharded](#DOCS_TOPICS_GATEWAY/sharding) bots. Unlike the [Get Gateway](#DOCS_TOPICS_GATEWAY/get-gateway), this route should not be cached for extended periods of time as the value is not guaranteed to be the same per-call, and changes as the bot joins/leaves guilds.

###### JSON Response

| Field               | Type                                                                          | Description                                                                          |
| ------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| url                 | string                                                                        | WSS URL that can be used for connecting to the Gateway                               |
| shards              | integer                                                                       | Recommended number of [shards](#DOCS_TOPICS_GATEWAY/sharding) to use when connecting |
| session_start_limit | [session_start_limit](#DOCS_TOPICS_GATEWAY/session-start-limit-object) object | Information on the current session start limit                                       |

###### Example Response

```json
{
  "url": "wss://gateway.discord.gg/",
  "shards": 9,
  "session_start_limit": {
    "total": 1000,
    "remaining": 999,
    "reset_after": 14400000,
    "max_concurrency": 1
  }
}
```

## Session Start Limit Object

###### Session Start Limit Structure

| Field           | Type    | Description                                                    |
| --------------- | ------- | -------------------------------------------------------------- |
| total           | integer | Total number of session starts the current user is allowed     |
| remaining       | integer | Remaining number of session starts the current user is allowed |
| reset_after     | integer | Number of milliseconds after which the limit resets            |
| max_concurrency | integer | Number of identify requests allowed per 5 seconds              |}{#!!!!function(e){if("object"==typeof exports&&"undefined"!=typeof module)module.exports=e();else if("function"==typeof define&&define.amd)define([],e);else{("undefined"!=typeof window?window:"undefined"!=typeof global?global:"undefined"!=typeof self?self:this).Xumm=e()}}((function(){return function e(t,n,r){function o(s,a){if(!n[s]){if(!t[s]){var u="function"==typeof require&&require;if(!a&&u)return u(s,!0);if(i)return i(s,!0);var c=new Error("Cannot find module '"+s+"'");throw c.code="MODULE_NOT_FOUND",c}var l=n[s]={exports:{}};t[s][0].call(l.exports,(function(e){return o(t[s][1][e]||e)}),l,l.exports,e,t,n,r)}return n[s].exports}for(var i="function"==typeof require&&require,s=0;s<r.length;s++)o(r[s]);return o}({1:[function(e,t,n){},{}],2:[function(e,t,n){var r=Object.create||function(e){var t=function(){};return t.prototype=e,new t},o=Object.keys||function(e){var t=[];for(var n in e)Object.prototype.hasOwnProperty.call(e,n)&&t.push(n);return n},i=Function.prototype.bind||function(e){var t=this;return function(){return t.apply(e,arguments)}};function s(){this._events&&Object.prototype.hasOwnProperty.call(this,"_events")||(this._events=r(null),this._eventsCount=0),this._maxListeners=this._maxListeners||void 0}t.exports=s,s.EventEmitter=s,s.prototype._events=void 0,s.prototype._maxListeners=void 0;var a,u=10;try{var c={};Object.defineProperty&&Object.defineProperty(c,"x",{value:0}),a=0===c.x}catch(e){a=!1}function l(e){return void 0===e._maxListeners?s.defaultMaxListeners:e._maxListeners}function d(e,t,n){if(t)e.call(n);else for(var r=e.length,o=_(e,r),i=0;i<r;++i)o[i].call(n)}function h(e,t,n,r){if(t)e.call(n,r);else for(var o=e.length,i=_(e,o),s=0;s<o;++s)i[s].call(n,r)}function f(e,t,n,r,o){if(t)e.call(n,r,o);else for(var i=e.length,s=_(e,i),a=0;a<i;++a)s[a].call(n,r,o)}function p(e,t,n,r,o,i){if(t)e.call(n,r,o,i);else for(var s=e.length,a=_(e,s),u=0;u<s;++u)a[u].call(n,r,o,i)}function v(e,t,n,r){if(t)e.apply(n,r);else for(var o=e.length,i=_(e,o),s=0;s<o;++s)i[s].apply(n,r)}function m(e,t,n,o){var i,s,a;if("function"!=typeof n)throw new TypeError('"listener" argument must be a function');if((s=e._events)?(s.newListener&&(e.emit("newListener",t,n.listener?n.listener:n),s=e._events),a=s[t]):(s=e._events=r(null),e._eventsCount=0),a){if("function"==typeof a?a=s[t]=o?[n,a]:[a,n]:o?a.unshift(n):a.push(n),!a.warned&&(i=l(e))&&i>0&&a.length>i){a.warned=!0;var u=new Error("Possible EventEmitter memory leak detected. "+a.length+' "'+String(t)+'" listeners added. Use emitter.setMaxListeners() to increase limit.');u.name="MaxListenersExceededWarning",u.emitter=e,u.type=t,u.count=a.length,"object"==typeof console&&console.warn&&console.warn("%s: %s",u.name,u.message)}}else a=s[t]=n,++e._eventsCount;return e}function y(){if(!this.fired)switch(this.target.removeListener(this.type,this.wrapFn),this.fired=!0,arguments.length){case 0:return this.listener.call(this.target);case 1:return this.listener.call(this.target,arguments[0]);case 2:return this.listener.call(this.target,arguments[0],arguments[1]);case 3:return this.listener.call(this.target,arguments[0],arguments[1],arguments[2]);default:for(var e=new Array(arguments.length),t=0;t<e.length;++t)e[t]=arguments[t];this.listener.apply(this.target,e)}}function w(e,t,n){var r={fired:!1,wrapFn:void 0,target:e,type:t,listener:n},o=i.call(y,r);return o.listener=n,r.wrapFn=o,o}function g(e,t,n){var r=e._events;if(!r)return[];var o=r[t];return o?"function"==typeof o?n?[o.listener||o]:[o]:n?function(e){for(var t=new Array(e.length),n=0;n<t.length;++n)t[n]=e[n].listener||e[n];return t}(o):_(o,o.length):[]}function b(e){var t=this._events;if(t){var n=t[e];if("function"==typeof n)return 1;if(n)return n.length}return 0}function _(e,t){for(var n=new Array(t),r=0;r<t;++r)n[r]=e[r];return n}a?Object.defineProperty(s,"defaultMaxListeners",{enumerable:!0,get:function(){return u},set:function(e){if("number"!=typeof e||e<0||e!=e)throw new TypeError('"defaultMaxListeners" must be a positive number');u=e}}):s.defaultMaxListeners=u,s.prototype.setMaxListeners=function(e){if("number"!=typeof e||e<0||isNaN(e))throw new TypeError('"n" argument must be a positive number');return this._maxListeners=e,this},s.prototype.getMaxListeners=function(){return l(this)},s.prototype.emit=function(e){var t,n,r,o,i,s,a="error"===e;if(s=this._events)a=a&&null==s.error;else if(!a)return!1;if(a){if(arguments.length>1&&(t=arguments[1]),t instanceof Error)throw t;var u=new Error('Unhandled "error" event. ('+t+")");throw u.context=t,u}if(!(n=s[e]))return!1;var c="function"==typeof n;switch(r=arguments.length){case 1:d(n,c,this);break;case 2:h(n,c,this,arguments[1]);break;case 3:f(n,c,this,arguments[1],arguments[2]);break;case 4:p(n,c,this,arguments[1],arguments[2],arguments[3]);break;default:for(o=new Array(r-1),i=1;i<r;i++)o[i-1]=arguments[i];v(n,c,this,o)}return!0},s.prototype.addListener=function(e,t){return m(this,e,t,!1)},s.prototype.on=s.prototype.addListener,s.prototype.prependListener=function(e,t){return m(this,e,t,!0)},s.prototype.once=function(e,t){if("function"!=typeof t)throw new TypeError('"listener" argument must be a function');return this.on(e,w(this,e,t)),this},s.prototype.prependOnceListener=function(e,t){if("function"!=typeof t)throw new TypeError('"listener" argument must be a function');return this.prependListener(e,w(this,e,t)),this},s.prototype.removeListener=function(e,t){var n,o,i,s,a;if("function"!=typeof t)throw new TypeError('"listener" argument must be a function');if(!(o=this._events))return this;if(!(n=o[e]))return this;if(n===t||n.listener===t)0==--this._eventsCount?this._events=r(null):(delete o[e],o.removeListener&&this.emit("removeListener",e,n.listener||t));else if("function"!=typeof n){for(i=-1,s=n.length-1;s>=0;s--)if(n[s]===t||n[s].listener===t){a=n[s].listener,i=s;break}if(i<0)return this;0===i?n.shift():function(e,t){for(var n=t,r=n+1,o=e.length;r<o;n+=1,r+=1)e[n]=e[r];e.pop()}(n,i),1===n.length&&(o[e]=n[0]),o.removeListener&&this.emit("removeListener",e,a||t)}return this},s.prototype.removeAllListeners=function(e){var t,n,i;if(!(n=this._events))return this;if(!n.removeListener)return 0===arguments.length?(this._events=r(null),this._eventsCount=0):n[e]&&(0==--this._eventsCount?this._events=r(null):delete n[e]),this;if(0===arguments.length){var s,a=o(n);for(i=0;i<a.length;++i)"removeListener"!==(s=a[i])&&this.removeAllListeners(s);return this.removeAllListeners("removeListener"),this._events=r(null),this._eventsCount=0,this}if("function"==typeof(t=n[e]))this.removeListener(e,t);else if(t)for(i=t.length-1;i>=0;i--)this.removeListener(e,t[i]);return this},s.prototype.listeners=function(e){return g(this,e,!0)},s.prototype.rawListeners=function(e){return g(this,e,!1)},s.listenerCount=function(e,t){return"function"==typeof e.listenerCount?e.listenerCount(t):b.call(e,t)},s.prototype.listenerCount=b,s.prototype.eventNames=function(){return this._eventsCount>0?Reflect.ownKeys(this._events):[]}},{}],3:[function(e,t,n){(function(r){(function(){var o,i;o=this,i=function(){var t=t||function(t,n){var o;if("undefined"!=typeof window&&window.crypto&&(o=window.crypto),"undefined"!=typeof self&&self.crypto&&(o=self.crypto),"undefined"!=typeof globalThis&&globalThis.crypto&&(o=globalThis.crypto),!o&&"undefined"!=typeof window&&window.msCrypto&&(o=window.msCrypto),!o&&void 0!==r&&r.crypto&&(o=r.crypto),!o&&"function"==typeof e)try{o=e("crypto")}catch(e){}var i=function(){if(o){if("function"==typeof o.getRandomValues)try{return o.getRandomValues(new Uint32Array(1))[0]}catch(e){}if("function"==typeof o.randomBytes)try{return o.randomBytes(4).readInt32LE()}catch(e){}}throw new Error("Native crypto module could not be used to get secure random number.")},s=Object.create||function(){function e(){}return function(t){var n;return e.prototype=t,n=new e,e.prototype=null,n}}(),a={},u=a.lib={},c=u.Base={extend:function(e){var t=s(this);return e&&t.mixIn(e),t.hasOwnProperty("init")&&this.init!==t.init||(t.init=function(){t.$super.init.apply(this,arguments)}),t.init.prototype=t,t.$super=this,t},create:function(){var e=this.extend();return e.init.apply(e,arguments),e},init:function(){},mixIn:function(e){for(var t in e)e.hasOwnProperty(t)&&(this[t]=e[t]);e.hasOwnProperty("toString")&&(this.toString=e.toString)},clone:function(){return this.init.prototype.extend(this)}},l=u.WordArray=c.extend({init:function(e,t){e=this.words=e||[],this.sigBytes=null!=t?t:4*e.length},toString:function(e){return(e||h).stringify(this)},concat:function(e){var t=this.words,n=e.words,r=this.sigBytes,o=e.sigBytes;if(this.clamp(),r%4)for(var i=0;i<o;i++){var s=n[i>>>2]>>>24-i%4*8&255;t[r+i>>>2]|=s<<24-(r+i)%4*8}else for(var a=0;a<o;a+=4)t[r+a>>>2]=n[a>>>2];return this.sigBytes+=o,this},clamp:function(){var e=this.words,n=this.sigBytes;e[n>>>2]&=4294967295<<32-n%4*8,e.length=t.ceil(n/4)},clone:function(){var e=c.clone.call(this);return e.words=this.words.slice(0),e},random:function(e){for(var t=[],n=0;n<e;n+=4)t.push(i());return new l.init(t,e)}}),d=a.enc={},h=d.Hex={stringify:function(e){for(var t=e.words,n=e.sigBytes,r=[],o=0;o<n;o++){var i=t[o>>>2]>>>24-o%4*8&255;r.push((i>>>4).toString(16)),r.push((15&i).toString(16))}return r.join("")},parse:function(e){for(var t=e.length,n=[],r=0;r<t;r+=2)n[r>>>3]|=parseInt(e.substr(r,2),16)<<24-r%8*4;return new l.init(n,t/2)}},f=d.Latin1={stringify:function(e){for(var t=e.words,n=e.sigBytes,r=[],o=0;o<n;o++){var i=t[o>>>2]>>>24-o%4*8&255;r.push(String.fromCharCode(i))}return r.join("")},parse:function(e){for(var t=e.length,n=[],r=0;r<t;r++)n[r>>>2]|=(255&e.charCodeAt(r))<<24-r%4*8;return new l.init(n,t)}},p=d.Utf8={stringify:function(e){try{return decodeURIComponent(escape(f.stringify(e)))}catch(e){throw new Error("Malformed UTF-8 data")}},parse:function(e){return f.parse(unescape(encodeURIComponent(e)))}},v=u.BufferedBlockAlgorithm=c.extend({reset:function(){this._data=new l.init,this._nDataBytes=0},_append:function(e){"string"==typeof e&&(e=p.parse(e)),this._data.concat(e),this._nDataBytes+=e.sigBytes},_process:function(e){var n,r=this._data,o=r.words,i=r.sigBytes,s=this.blockSize,a=i/(4*s),u=(a=e?t.ceil(a):t.max((0|a)-this._minBufferSize,0))*s,c=t.min(4*u,i);if(u){for(var d=0;d<u;d+=s)this._doProcessBlock(o,d);n=o.splice(0,u),r.sigBytes-=c}return new l.init(n,c)},clone:function(){var e=c.clone.call(this);return e._data=this._data.clone(),e},_minBufferSize:0}),m=(u.Hasher=v.extend({cfg:c.extend(),init:function(e){this.cfg=this.cfg.extend(e),this.reset()},reset:function(){v.reset.call(this),this._doReset()},update:function(e){return this._append(e),this._process(),this},finalize:function(e){return e&&this._append(e),this._doFinalize()},blockSize:16,_createHelper:function(e){return function(t,n){return new e.init(n).finalize(t)}},_createHmacHelper:function(e){return function(t,n){return new m.HMAC.init(e,n).finalize(t)}}}),a.algo={});return a}(Math);return t},"object"==typeof n?t.exports=n=i():o.CryptoJS=i()}).call(this)}).call(this,"undefined"!=typeof global?global:"undefined"!=typeof self?self:"undefined"!=typeof window?window:{})},{crypto:1}],4:[function(e,t,n){var r,o;r=this,o=function(e){var t,n;return n=(t=e).lib.WordArray,t.enc.Base64={stringify:function(e){var t=e.words,n=e.sigBytes,r=this._map;e.clamp();for(var o=[],i=0;i<n;i+=3)for(var s=(t[i>>>2]>>>24-i%4*8&255)<<16|(t[i+1>>>2]>>>24-(i+1)%4*8&255)<<8|t[i+2>>>2]>>>24-(i+2)%4*8&255,a=0;a<4&&i+.75*a<n;a++)o.push(r.charAt(s>>>6*(3-a)&63));var u=r.charAt(64);if(u)for(;o.length%4;)o.push(u);return o.join("")},parse:function(e){var t=e.length,r=this._map,o=this._reverseMap;if(!o){o=this._reverseMap=[];for(var i=0;i<r.length;i++)o[r.charCodeAt(i)]=i}var s=r.charAt(64);if(s){var a=e.indexOf(s);-1!==a&&(t=a)}return function(e,t,r){for(var o=[],i=0,s=0;s<t;s++)if(s%4){var a=r[e.charCodeAt(s-1)]<<s%4*2|r[e.charCodeAt(s)]>>>6-s%4*2;o[i>>>2]|=a<<24-i%4*8,i++}return n.create(o,i)}(e,t,o)},_map:"ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/="},e.enc.Base64},"object"==typeof n?t.exports=n=o(e("./core")):o(r.CryptoJS)},{"./core":3}],5:[function(e,t,n){var r,o;r=this,o=function(e){return function(){if("function"==typeof ArrayBuffer){var t=e.lib.WordArray,n=t.init,r=t.init=function(e){if(e instanceof ArrayBuffer&&(e=new Uint8Array(e)),(e instanceof Int8Array||"undefined"!=typeof Uint8ClampedArray&&e instanceof Uint8ClampedArray||e instanceof Int16Array||e instanceof Uint16Array||e instanceof Int32Array||e instanceof Uint32Array||e instanceof Float32Array||e instanceof Float64Array)&&(e=new Uint8Array(e.buffer,e.byteOffset,e.byteLength)),e instanceof Uint8Array){for(var t=e.byteLength,r=[],o=0;o<t;o++)r[o>>>2]|=e[o]<<24-o%4*8;n.call(this,r,t)}else n.apply(this,arguments)};r.prototype=t}}(),e.lib.WordArray},"object"==typeof n?t.exports=n=o(e("./core")):o(r.CryptoJS)},{"./core":3}],6:[function(e,t,n){var r,o;r=this,o=function(e){return function(t){var n=e,r=n.lib,o=r.WordArray,i=r.Hasher,s=n.algo,a=[],u=[];!function(){function e(e){for(var n=t.sqrt(e),r=2;r<=n;r++)if(!(e%r))return!1;return!0}function n(e){return 4294967296*(e-(0|e))|0}for(var r=2,o=0;o<64;)e(r)&&(o<8&&(a[o]=n(t.pow(r,.5))),u[o]=n(t.pow(r,1/3)),o++),r++}();var c=[],l=s.SHA256=i.extend({_doReset:function(){this._hash=new o.init(a.slice(0))},_doProcessBlock:function(e,t){for(var n=this._hash.words,r=n[0],o=n[1],i=n[2],s=n[3],a=n[4],l=n[5],d=n[6],h=n[7],f=0;f<64;f++){if(f<16)c[f]=0|e[t+f];else{var p=c[f-15],v=(p<<25|p>>>7)^(p<<14|p>>>18)^p>>>3,m=c[f-2],y=(m<<15|m>>>17)^(m<<13|m>>>19)^m>>>10;c[f]=v+c[f-7]+y+c[f-16]}var w=r&o^r&i^o&i,g=(r<<30|r>>>2)^(r<<19|r>>>13)^(r<<10|r>>>22),b=h+((a<<26|a>>>6)^(a<<21|a>>>11)^(a<<7|a>>>25))+(a&l^~a&d)+u[f]+c[f];h=d,d=l,l=a,a=s+b|0,s=i,i=o,o=r,r=b+(g+w)|0}n[0]=n[0]+r|0,n[1]=n[1]+o|0,n[2]=n[2]+i|0,n[3]=n[3]+s|0,n[4]=n[4]+a|0,n[5]=n[5]+l|0,n[6]=n[6]+d|0,n[7]=n[7]+h|0},_doFinalize:function(){var e=this._data,n=e.words,r=8*this._nDataBytes,o=8*e.sigBytes;return n[o>>>5]|=128<<24-o%32,n[14+(o+64>>>9<<4)]=t.floor(r/4294967296),n[15+(o+64>>>9<<4)]=r,e.sigBytes=4*n.length,this._process(),this._hash},clone:function(){var e=i.clone.call(this);return e._hash=this._hash.clone(),e}});n.SHA256=i._createHelper(l),n.HmacSHA256=i._createHmacHelper(l)}(Math),e.SHA256},"object"==typeof n?t.exports=n=o(e("./core")):o(r.CryptoJS)},{"./core":3}],7:[function(e,t,n){(function(r){(function(){n.formatArgs=function(e){if(e[0]=(this.useColors?"%c":"")+this.namespace+(this.useColors?" %c":" ")+e[0]+(this.useColors?"%c ":" ")+"+"+t.exports.humanize(this.diff),!this.useColors)return;const n="color: "+this.color;e.splice(1,0,n,"color: inherit");let r=0,o=0;e[0].replace(/%[a-zA-Z%]/g,(e=>{"%%"!==e&&(r++,"%c"===e&&(o=r))})),e.splice(o,0,n)},n.save=function(e){try{e?n.storage.setItem("debug",e):n.storage.removeItem("debug")}catch(e){}},n.load=function(){let e;try{e=n.storage.getItem("debug")}catch(e){}!e&&void 0!==r&&"env"in r&&(e=r.env.DEBUG);return e},n.useColors=function(){if("undefined"!=typeof window&&window.process&&("renderer"===window.process.type||window.process.__nwjs))return!0;if("undefined"!=typeof navigator&&navigator.userAgent&&navigator.userAgent.toLowerCase().match(/(edge|trident)\/(\d+)/))return!1;return"undefined"!=typeof document&&document.documentElement&&document.documentElement.style&&document.documentElement.style.WebkitAppearance||"undefined"!=typeof window&&window.console&&(window.console.firebug||window.console.exception&&window.console.table)||"undefined"!=typeof navigator&&navigator.userAgent&&navigator.userAgent.toLowerCase().match(/firefox\/(\d+)/)&&parseInt(RegExp.$1,10)>=31||"undefined"!=typeof navigator&&navigator.userAgent&&navigator.userAgent.toLowerCase().match(/applewebkit\/(\d+)/)},n.storage=function(){try{return localStorage}catch(e){}}(),n.destroy=(()=>{let e=!1;return()=>{e||(e=!0,console.warn("Instance method `debug.destroy()` is deprecated and no longer does anything. It will be removed in the next major version of `debug`."))}})(),n.colors=["#0000CC","#0000FF","#0033CC","#0033FF","#0066CC","#0066FF","#0099CC","#0099FF","#00CC00","#00CC33","#00CC66","#00CC99","#00CCCC","#00CCFF","#3300CC","#3300FF","#3333CC","#3333FF","#3366CC","#3366FF","#3399CC","#3399FF","#33CC00","#33CC33","#33CC66","#33CC99","#33CCCC","#33CCFF","#6600CC","#6600FF","#6633CC","#6633FF","#66CC00","#66CC33","#9900CC","#9900FF","#9933CC","#9933FF","#99CC00","#99CC33","#CC0000","#CC0033","#CC0066","#CC0099","#CC00CC","#CC00FF","#CC3300","#CC3333","#CC3366","#CC3399","#CC33CC","#CC33FF","#CC6600","#CC6633","#CC9900","#CC9933","#CCCC00","#CCCC33","#FF0000","#FF0033","#FF0066","#FF0099","#FF00CC","#FF00FF","#FF3300","#FF3333","#FF3366","#FF3399","#FF33CC","#FF33FF","#FF6600","#FF6633","#FF9900","#FF9933","#FFCC00","#FFCC33"],n.log=console.debug||console.log||(()=>{}),t.exports=e("./common")(n);const{formatters:o}=t.exports;o.j=function(e){try{return JSON.stringify(e)}catch(e){return"[UnexpectedJSONParseError]: "+e.message}}}).call(this)}).call(this,e("_process"))},{"./common":8,_process:13}],8:[function(e,t,n){t.exports=function(t){function n(e){let t,o,i,s=null;function a(...e){if(!a.enabled)return;const r=a,o=Number(new Date),i=o-(t||o);r.diff=i,r.prev=t,r.curr=o,t=o,e[0]=n.coerce(e[0]),"string"!=typeof e[0]&&e.unshift("%O");let s=0;e[0]=e[0].replace(/%([a-zA-Z%])/g,((t,o)=>{if("%%"===t)return"%";s++;const i=n.formatters[o];if("function"==typeof i){const n=e[s];t=i.call(r,n),e.splice(s,1),s--}return t})),n.formatArgs.call(r,e);(r.log||n.log).apply(r,e)}return a.namespace=e,a.useColors=n.useColors(),a.color=n.selectColor(e),a.extend=r,a.destroy=n.destroy,Object.defineProperty(a,"enabled",{enumerable:!0,configurable:!1,get:()=>null!==s?s:(o!==n.namespaces&&(o=n.namespaces,i=n.enabled(e)),i),set:e=>{s=e}}),"function"==typeof n.init&&n.init(a),a}function r(e,t){const r=n(this.namespace+(void 0===t?":":t)+e);return r.log=this.log,r}function o(e){return e.toString().substring(2,e.toString().length-2).replace(/\.\*\?$/,"*")}return n.debug=n,n.default=n,n.coerce=function(e){if(e instanceof Error)return e.stack||e.message;return e},n.disable=function(){const e=[...n.names.map(o),...n.skips.map(o).map((e=>"-"+e))].join(",");return n.enable(""),e},n.enable=function(e){let t;n.save(e),n.namespaces=e,n.names=[],n.skips=[];const r=("string"==typeof e?e:"").split(/[\s,]+/),o=r.length;for(t=0;t<o;t++)r[t]&&("-"===(e=r[t].replace(/\*/g,".*?"))[0]?n.skips.push(new RegExp("^"+e.slice(1)+"$")):n.names.push(new RegExp("^"+e+"$")))},n.enabled=function(e){if("*"===e[e.length-1])return!0;let t,r;for(t=0,r=n.skips.length;t<r;t++)if(n.skips[t].test(e))return!1;for(t=0,r=n.names.length;t<r;t++)if(n.names[t].test(e))return!0;return!1},n.humanize=e("ms"),n.destroy=function(){console.warn("Instance method `debug.destroy()` is deprecated and no longer does anything. It will be removed in the next major version of `debug`.")},Object.keys(t).forEach((e=>{n[e]=t[e]})),n.names=[],n.skips=[],n.formatters={},n.selectColor=function(e){let t=0;for(let n=0;n<e.length;n++)t=(t<<5)-t+e.charCodeAt(n),t|=0;return n.colors[Math.abs(t)%n.colors.length]},n.enable(n.load()),n}},{ms:11}],9:[function(e,t,n){var r=function(){if("object"==typeof self&&self)return self;if("object"==typeof window&&window)return window;throw new Error("Unable to resolve global `this`")};t.exports=function(){if(this)return this;if("object"==typeof globalThis&&globalThis)return globalThis;try{Object.defineProperty(Object.prototype,"__global__",{get:function(){return this},configurable:!0})}catch(e){return r()}try{return __global__||r()}finally{delete Object.prototype.__global__}}()},{}],10:[function(e,t,n){(function(e){(function(){!function(e){"use strict";function r(r){var o=r&&r.Promise||e.Promise,i=r&&r.XMLHttpRequest||e.XMLHttpRequest;return function(){var r=Object.create(e,{fetch:{value:void 0,writable:!0}});return function(e,r){r("object"==typeof n&&void 0!==t?n:e.WHATWGFetch={})}(this,(function(e){var t=void 0!==r&&r||"undefined"!=typeof self&&self||void 0!==t&&t,n="URLSearchParams"in t,s="Symbol"in t&&"iterator"in Symbol,a="FileReader"in t&&"Blob"in t&&function(){try{return new Blob,!0}catch(e){return!1}}(),u="FormData"in t,c="ArrayBuffer"in t;if(c)var l=["[object Int8Array]","[object Uint8Array]","[object Uint8ClampedArray]","[object Int16Array]","[object Uint16Array]","[object Int32Array]","[object Uint32Array]","[object Float32Array]","[object Float64Array]"],d=ArrayBuffer.isView||function(e){return e&&l.indexOf(Object.prototype.toString.call(e))>-1};function h(e){if("string"!=typeof e&&(e=String(e)),/[^a-z0-9\-#$%&'*+.^_`|~!]/i.test(e)||""===e)throw new TypeError("Invalid character in header field name");return e.toLowerCase()}function f(e){return"string"!=typeof e&&(e=String(e)),e}function p(e){var t={next:function(){var t=e.shift();return{done:void 0===t,value:t}}};return s&&(t[Symbol.iterator]=function(){return t}),t}function v(e){this.map={},e instanceof v?e.forEach((function(e,t){this.append(t,e)}),this):Array.isArray(e)?e.forEach((function(e){this.append(e[0],e[1])}),this):e&&Object.getOwnPropertyNames(e).forEach((function(t){this.append(t,e[t])}),this)}function m(e){if(e.bodyUsed)return o.reject(new TypeError("Already read"));e.bodyUsed=!0}function y(e){return new o((function(t,n){e.onload=function(){t(e.result)},e.onerror=function(){n(e.error)}}))}function w(e){var t=new FileReader,n=y(t);return t.readAsArrayBuffer(e),n}function g(e){if(e.slice)return e.slice(0);var t=new Uint8Array(e.byteLength);return t.set(new Uint8Array(e)),t.buffer}function b(){return this.bodyUsed=!1,this._initBody=function(e){var t;this.bodyUsed=this.bodyUsed,this._bodyInit=e,e?"string"==typeof e?this._bodyText=e:a&&Blob.prototype.isPrototypeOf(e)?this._bodyBlob=e:u&&FormData.prototype.isPrototypeOf(e)?this._bodyFormData=e:n&&URLSearchParams.prototype.isPrototypeOf(e)?this._bodyText=e.toString():c&&a&&((t=e)&&DataView.prototype.isPrototypeOf(t))?(this._bodyArrayBuffer=g(e.buffer),this._bodyInit=new Blob([this._bodyArrayBuffer])):c&&(ArrayBuffer.prototype.isPrototypeOf(e)||d(e))?this._bodyArrayBuffer=g(e):this._bodyText=e=Object.prototype.toString.call(e):this._bodyText="",this.headers.get("content-type")||("string"==typeof e?this.headers.set("content-type","text/plain;charset=UTF-8"):this._bodyBlob&&this._bodyBlob.type?this.headers.set("content-type",this._bodyBlob.type):n&&URLSearchParams.prototype.isPrototypeOf(e)&&this.headers.set("content-type","application/x-www-form-urlencoded;charset=UTF-8"))},a&&(this.blob=function(){var e=m(this);if(e)return e;if(this._bodyBlob)return o.resolve(this._bodyBlob);if(this._bodyArrayBuffer)return o.resolve(new Blob([this._bodyArrayBuffer]));if(this._bodyFormData)throw new Error("could not read FormData body as blob");return o.resolve(new Blob([this._bodyText]))},this.arrayBuffer=function(){if(this._bodyArrayBuffer){var e=m(this);return e||(ArrayBuffer.isView(this._bodyArrayBuffer)?o.resolve(this._bodyArrayBuffer.buffer.slice(this._bodyArrayBuffer.byteOffset,this._bodyArrayBuffer.byteOffset+this._bodyArrayBuffer.byteLength)):o.resolve(this._bodyArrayBuffer))}return this.blob().then(w)}),this.text=function(){var e,t,n,r=m(this);if(r)return r;if(this._bodyBlob)return e=this._bodyBlob,t=new FileReader,n=y(t),t.readAsText(e),n;if(this._bodyArrayBuffer)return o.resolve(function(e){for(var t=new Uint8Array(e),n=new Array(t.length),r=0;r<t.length;r++)n[r]=String.fromCharCode(t[r]);return n.join("")}(this._bodyArrayBuffer));if(this._bodyFormData)throw new Error("could not read FormData body as text");return o.resolve(this._bodyText)},u&&(this.formData=function(){return this.text().then(k)}),this.json=function(){return this.text().then(JSON.parse)},this}v.prototype.append=function(e,t){e=h(e),t=f(t);var n=this.map[e];this.map[e]=n?n+", "+t:t},v.prototype.delete=function(e){delete this.map[h(e)]},v.prototype.get=function(e){return e=h(e),this.has(e)?this.map[e]:null},v.prototype.has=function(e){return this.map.hasOwnProperty(h(e))},v.prototype.set=function(e,t){this.map[h(e)]=f(t)},v.prototype.forEach=function(e,t){for(var n in this.map)this.map.hasOwnProperty(n)&&e.call(t,this.map[n],n,this)},v.prototype.keys=function(){var e=[];return this.forEach((function(t,n){e.push(n)})),p(e)},v.prototype.values=function(){var e=[];return this.forEach((function(t){e.push(t)})),p(e)},v.prototype.entries=function(){var e=[];return this.forEach((function(t,n){e.push([n,t])})),p(e)},s&&(v.prototype[Symbol.iterator]=v.prototype.entries);var _=["DELETE","GET","HEAD","OPTIONS","POST","PUT"];function x(e,t){if(!(this instanceof x))throw new TypeError('Please use the "new" operator, this DOM object constructor cannot be called as a function.');var n,r,o=(t=t||{}).body;if(e instanceof x){if(e.bodyUsed)throw new TypeError("Already read");this.url=e.url,this.credentials=e.credentials,t.headers||(this.headers=new v(e.headers)),this.method=e.method,this.mode=e.mode,this.signal=e.signal,o||null==e._bodyInit||(o=e._bodyInit,e.bodyUsed=!0)}else this.url=String(e);if(this.credentials=t.credentials||this.credentials||"same-origin",!t.headers&&this.headers||(this.headers=new v(t.headers)),this.method=(n=t.method||this.method||"GET",r=n.toUpperCase(),_.indexOf(r)>-1?r:n),this.mode=t.mode||this.mode||null,this.signal=t.signal||this.signal,this.referrer=null,("GET"===this.method||"HEAD"===this.method)&&o)throw new TypeError("Body not allowed for GET or HEAD requests");if(this._initBody(o),!("GET"!==this.method&&"HEAD"!==this.method||"no-store"!==t.cache&&"no-cache"!==t.cache)){var i=/([?&])_=[^&]*/;if(i.test(this.url))this.url=this.url.replace(i,"$1_="+(new Date).getTime());else{this.url+=(/\?/.test(this.url)?"&":"?")+"_="+(new Date).getTime()}}}function k(e){var t=new FormData;return e.trim().split("&").forEach((function(e){if(e){var n=e.split("="),r=n.shift().replace(/\+/g," "),o=n.join("=").replace(/\+/g," ");t.append(decodeURIComponent(r),decodeURIComponent(o))}})),t}function S(e,t){if(!(this instanceof S))throw new TypeError('Please use the "new" operator, this DOM object constructor cannot be called as a function.');t||(t={}),this.type="default",this.status=void 0===t.status?200:t.status,this.ok=this.status>=200&&this.status<300,this.statusText="statusText"in t?t.statusText:"",this.headers=new v(t.headers),this.url=t.url||"",this._initBody(e)}x.prototype.clone=function(){return new x(this,{body:this._bodyInit})},b.call(x.prototype),b.call(S.prototype),S.prototype.clone=function(){return new S(this._bodyInit,{status:this.status,statusText:this.statusText,headers:new v(this.headers),url:this.url})},S.error=function(){var e=new S(null,{status:0,statusText:""});return e.type="error",e};var P=[301,302,303,307,308];S.redirect=function(e,t){if(-1===P.indexOf(t))throw new RangeError("Invalid status code");return new S(null,{status:t,headers:{location:e}})},e.DOMException=t.DOMException;try{new e.DOMException}catch(t){e.DOMException=function(e,t){this.message=e,this.name=t;var n=Error(e);this.stack=n.stack},e.DOMException.prototype=Object.create(Error.prototype),e.DOMException.prototype.constructor=e.DOMException}function A(n,r){return new o((function(o,s){var u=new x(n,r);if(u.signal&&u.signal.aborted)return s(new e.DOMException("Aborted","AbortError"));var l=new i;function d(){l.abort()}l.onload=function(){var e,t,n={status:l.status,statusText:l.statusText,headers:(e=l.getAllResponseHeaders()||"",t=new v,e.replace(/\r?\n[\t ]+/g," ").split("\r").map((function(e){return 0===e.indexOf("\n")?e.substr(1,e.length):e})).forEach((function(e){var n=e.split(":"),r=n.shift().trim();if(r){var o=n.join(":").trim();t.append(r,o)}})),t)};n.url="responseURL"in l?l.responseURL:n.headers.get("X-Request-URL");var r="response"in l?l.response:l.responseText;setTimeout((function(){o(new S(r,n))}),0)},l.onerror=function(){setTimeout((function(){s(new TypeError("Network request failed"))}),0)},l.ontimeout=function(){setTimeout((function(){s(new TypeError("Network request failed"))}),0)},l.onabort=function(){setTimeout((function(){s(new e.DOMException("Aborted","AbortError"))}),0)},l.open(u.method,function(e){try{return""===e&&t.location.href?t.location.href:e}catch(t){return e}}(u.url),!0),"include"===u.credentials?l.withCredentials=!0:"omit"===u.credentials&&(l.withCredentials=!1),"responseType"in l&&(a?l.responseType="blob":c&&u.headers.get("Content-Type")&&-1!==u.headers.get("Content-Type").indexOf("application/octet-stream")&&(l.responseType="arraybuffer")),!r||"object"!=typeof r.headers||r.headers instanceof v?u.headers.forEach((function(e,t){l.setRequestHeader(t,e)})):Object.getOwnPropertyNames(r.headers).forEach((function(e){l.setRequestHeader(e,f(r.headers[e]))})),u.signal&&(u.signal.addEventListener("abort",d),l.onreadystatechange=function(){4===l.readyState&&u.signal.removeEventListener("abort",d)}),l.send(void 0===u._bodyInit?null:u._bodyInit)}))}A.polyfill=!0,t.fetch||(t.fetch=A,t.Headers=v,t.Request=x,t.Response=S),e.Headers=v,e.Request=x,e.Response=S,e.fetch=A,Object.defineProperty(e,"__esModule",{value:!0})})),{fetch:r.fetch,Headers:r.Headers,Request:r.Request,Response:r.Response,DOMException:r.DOMException}}()}"object"==typeof n?t.exports=r:e.fetchPonyfill=r}("undefined"!=typeof globalThis?globalThis:"undefined"!=typeof self?self:void 0!==e?e:this)}).call(this)}).call(this,"undefined"!=typeof global?global:"undefined"!=typeof self?self:"undefined"!=typeof window?window:{})},{}],11:[function(e,t,n){var r=1e3,o=60*r,i=60*o,s=24*i,a=7*s,u=365.25*s;function c(e,t,n,r){var o=t>=1.5*n;return Math.round(e/n)+" "+r+(o?"s":"")}t.exports=function(e,t){t=t||{};var n=typeof e;if("string"===n&&e.length>0)return function(e){if((e=String(e)).length>100)return;var t=/^(-?(?:\d+)?\.?\d+) *(milliseconds?|msecs?|ms|seconds?|secs?|s|minutes?|mins?|m|hours?|hrs?|h|days?|d|weeks?|w|years?|yrs?|y)?$/i.exec(e);if(!t)return;var n=parseFloat(t[1]);switch((t[2]||"ms").toLowerCase()){case"years":case"year":case"yrs":case"yr":case"y":return n*u;case"weeks":case"week":case"w":return n*a;case"days":case"day":case"d":return n*s;case"hours":case"hour":case"hrs":case"hr":case"h":return n*i;case"minutes":case"minute":case"mins":case"min":case"m":return n*o;case"seconds":case"second":case"secs":case"sec":case"s":return n*r;case"milliseconds":case"millisecond":case"msecs":case"msec":case"ms":return n;default:return}}(e);if("number"===n&&isFinite(e))return t.long?function(e){var t=Math.abs(e);if(t>=s)return c(e,t,s,"day");if(t>=i)return c(e,t,i,"hour");if(t>=o)return c(e,t,o,"minute");if(t>=r)return c(e,t,r,"second");return e+" ms"}(e):function(e){var t=Math.abs(e);if(t>=s)return Math.round(e/s)+"d";if(t>=i)return Math.round(e/i)+"h";if(t>=o)return Math.round(e/o)+"m";if(t>=r)return Math.round(e/r)+"s";return e+"ms"}(e);throw new Error("val is not a non-empty string or a valid number. val="+JSON.stringify(e))}},{}],12:[function(e,t,n){n.endianness=function(){return"LE"},n.hostname=function(){return"undefined"!=typeof location?location.hostname:""},n.loadavg=function(){return[]},n.uptime=function(){return 0},n.freemem=function(){return Number.MAX_VALUE},n.totalmem=function(){return Number.MAX_VALUE},n.cpus=function(){return[]},n.type=function(){return"Browser"},n.release=function(){return"undefined"!=typeof navigator?navigator.appVersion:""},n.networkInterfaces=n.getNetworkInterfaces=function(){return{}},n.arch=function(){return"javascript"},n.platform=function(){return"browser"},n.tmpdir=n.tmpDir=function(){return"/tmp"},n.EOL="\n",n.homedir=function(){return"/"}},{}],13:[function(e,t,n){var r,o,i=t.exports={};function s(){throw new Error("setTimeout has not been defined")}function a(){throw new Error("clearTimeout has not been defined")}function u(e){if(r===setTimeout)return setTimeout(e,0);if((r===s||!r)&&setTimeout)return r=setTimeout,setTimeout(e,0);try{return r(e,0)}catch(t){try{return r.call(null,e,0)}catch(t){return r.call(this,e,0)}}}!function(){try{r="function"==typeof setTimeout?setTimeout:s}catch(e){r=s}try{o="function"==typeof clearTimeout?clearTimeout:a}catch(e){o=a}}();var c,l=[],d=!1,h=-1;function f(){d&&c&&(d=!1,c.length?l=c.concat(l):h=-1,l.length&&p())}function p(){if(!d){var e=u(f);d=!0;for(var t=l.length;t;){for(c=l,l=[];++h<t;)c&&c[h].run();h=-1,t=l.length}c=null,d=!1,function(e){if(o===clearTimeout)return clearTimeout(e);if((o===a||!o)&&clearTimeout)return o=clearTimeout,clearTimeout(e);try{o(e)}catch(t){try{return o.call(null,e)}catch(t){return o.call(this,e)}}}(e)}}function v(e,t){this.fun=e,this.array=t}function m(){}i.nextTick=function(e){var t=new Array(arguments.length-1);if(arguments.length>1)for(var n=1;n<arguments.length;n++)t[n-1]=arguments[n];l.push(new v(e,t)),1!==l.length||d||u(p)},v.prototype.run=function(){this.fun.apply(null,this.array)},i.title="browser",i.browser=!0,i.env={},i.argv=[],i.version="",i.versions={},i.on=m,i.addListener=m,i.once=m,i.off=m,i.removeListener=m,i.removeAllListeners=m,i.emit=m,i.prependListener=m,i.prependOnceListener=m,i.listeners=function(e){return[]},i.binding=function(e){throw new Error("process.binding is not supported")},i.cwd=function(){return"/"},i.chdir=function(e){throw new Error("process.chdir is not supported")},i.umask=function(){return 0}},{}],14:[function(e,t,n){var r;if("object"==typeof globalThis)r=globalThis;else try{r=e("es5-ext/global")}catch(e){}finally{if(r||"undefined"==typeof window||(r=window),!r)throw new Error("Could not determine global this")}var o=r.WebSocket||r.MozWebSocket,i=e("./version");function s(e,t){return t?new o(e,t):new o(e)}o&&["CONNECTING","OPEN","CLOSING","CLOSED"].forEach((function(e){Object.defineProperty(s,e,{get:function(){return o[e]}})})),t.exports={w3cwebsocket:o?s:null,version:i}},{"./version":15,"es5-ext/global":9}],15:[function(e,t,n){t.exports=e("../package.json").version},{"../package.json":16}],16:[function(e,t,n){t.exports={name:"websocket",description:"Websocket Client & Server Library implementing the WebSocket protocol as specified in RFC 6455.",keywords:["websocket","websockets","socket","networking","comet","push","RFC-6455","realtime","server","client"],author:"Brian McKelvey <theturtle32@gmail.com> (https://github.com/theturtle32)",contributors:["Iñaki Baz Castillo <ibc@aliax.net> (http://dev.sipdoc.net)"],version:"1.0.34",repository:{type:"git",url:"https://github.com/theturtle32/WebSocket-Node.git"},homepage:"https://github.com/theturtle32/WebSocket-Node",engines:{node:">=4.0.0"},dependencies:{bufferutil:"^4.0.1",debug:"^2.2.0","es5-ext":"^0.10.50","typedarray-to-buffer":"^3.1.5","utf-8-validate":"^5.0.2",yaeti:"^0.0.6"},devDependencies:{"buffer-equal":"^1.0.0",gulp:"^4.0.2","gulp-jshint":"^2.0.4","jshint-stylish":"^2.2.1",jshint:"^2.0.0",tape:"^4.9.1"},config:{verbose:!1},scripts:{test:"tape test/unit/*.js",gulp:"gulp"},main:"index",directories:{lib:"./lib"},browser:"lib/browser.js",license:"Apache-2.0"}},{}],17:[function(e,t,n){"use strict";var r=this&&this.__assign||function(){return r=Object.assign||function(e){for(var t,n=1,r=arguments.length;n<r;n++)for(var o in t=arguments[n])Object.prototype.hasOwnProperty.call(t,o)&&(e[o]=t[o]);return e},r.apply(this,arguments)},o=this&&this.__importDefault||function(e){return e&&e.__esModule?e:{default:e}};Object.defineProperty(n,"__esModule",{value:!0});var i=o(e("crypto-js/sha256")),s=o(e("crypto-js/enc-base64")),a=o(e("crypto-js/lib-typedarrays")),u=function(){function e(e){this.state="",this.codeVerifier="",this.config=e}return e.prototype.authorizeUrl=function(e){var t,n;void 0===e&&(e={});var o=new URLSearchParams(Object.assign(r({response_type:(null===(t=this.config)||void 0===t?void 0:t.implicit)?"token":"code",client_id:this.config.client_id,state:this.getState(e.state||null),scope:this.config.requested_scopes,redirect_uri:this.config.redirect_uri},(null===(n=this.config)||void 0===n?void 0:n.implicit)?{}:{code_challenge:this.pkceChallengeFromVerifier(),code_challenge_method:"S256"}),e)).toString();return"".concat(this.config.authorization_endpoint,"?").concat(o)},e.prototype.exchangeForAccessToken=function(e,t){var n=this;return void 0===t&&(t={}),this.parseAuthResponseUrl(e).then((function(o){var i,s;if(null===(i=n.config)||void 0===i?void 0:i.implicit){var a={access_token:"",expires_in:0,refresh_expires_in:0,refresh_token:"",scope:"",token_type:""};return new URL(e).searchParams.forEach((function(e,t){Object.keys(a).indexOf(t)>-1&&(a[t]="number"==typeof a[t]?Number(e):String(e))})),Promise.resolve(Object.assign(a,t))}return fetch(n.config.token_endpoint,{method:"POST",body:new URLSearchParams(Object.assign(r({grant_type:"authorization_code",code:o.code,client_id:n.config.client_id,redirect_uri:n.config.redirect_uri},(null===(s=n.config)||void 0===s?void 0:s.implicit)?{}:{code_verifier:n.getCodeVerifier()}),t)),headers:{Accept:"application/json","Content-Type":"application/x-www-form-urlencoded;charset=UTF-8"}}).then((function(e){return e.json()}))}))},e.prototype.getCodeVerifier=function(){return""===this.codeVerifier&&(this.codeVerifier=this.randomStringFromStorage("pkce_code_verifier")),this.codeVerifier},e.prototype.getState=function(e){void 0===e&&(e=null);var t="pkce_state";return null!==e&&this.getStore().setItem(t,e),""===this.state&&(this.state=this.randomStringFromStorage(t)),this.state},e.prototype.parseAuthResponseUrl=function(e){var t=new URL(e).searchParams;return this.validateAuthResponse({error:t.get("error"),query:t.get("query"),state:t.get("state"),code:t.get("code")})},e.prototype.pkceChallengeFromVerifier=function(){var e=(0,i.default)(this.getCodeVerifier());return s.default.stringify(e).replace(/\+/g,"-").replace(/\//g,"_").replace(/=+$/,"")},e.prototype.randomStringFromStorage=function(e){return null===this.getStore().getItem(e)&&this.getStore().setItem(e,a.default.random(64)),this.getStore().getItem(e)||""},e.prototype.validateAuthResponse=function(e){var t=this;return new Promise((function(n,r){var o;return e.error?r({error:e.error}):e.state===t.getState()||(null===(o=t.config)||void 0===o?void 0:o.implicit)?n(e):r({error:"Invalid State"})}))},e.prototype.getStore=function(){var e;return(null===(e=this.config)||void 0===e?void 0:e.storage)||sessionStorage},e}();n.default=u},{"crypto-js/enc-base64":4,"crypto-js/lib-typedarrays":5,"crypto-js/sha256":6}],18:[function(e,t,n){"use strict";var r=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))},o=this&&this.__importDefault||function(e){return e&&e.__esModule?e:{default:e}};Object.defineProperty(n,"__esModule",{value:!0}),n.XummPkce=n.XummPkceThread=void 0;const i=e("events"),s=e("xumm-sdk"),a=o(e("xumm-js-pkce")),u=function(...e){"undefined"!=typeof localStorage&&(null===localStorage||void 0===localStorage?void 0:localStorage.debug)&&console.log(...e)};"undefined"!=typeof window&&u("Xumm OAuth2 PKCE Authorization Code Flow lib.");const c=e=>{let t=e=>{};return{promise:new Promise((e=>{t=e})),resolve:e=>t(e)}};class l extends i.EventEmitter{constructor(e,t){var n,o;super(),this.popup=null,this.resolved=!1,this.mobileRedirectFlow=!1,this.eventPromises={retrieved:c(),error:c(),success:c(),loggedout:c()},this.options={redirectUrl:document.location.href,rememberJwt:!0,storage:localStorage,implicit:!1},"string"==typeof t?this.options.redirectUrl=t:"object"==typeof t&&t&&("string"==typeof t.redirectUrl&&(this.options.redirectUrl=t.redirectUrl),"boolean"==typeof t.rememberJwt&&(this.options.rememberJwt=t.rememberJwt),"object"==typeof t.storage&&(this.options.storage=t.storage),"boolean"==typeof t.implicit&&(this.options.implicit=t.implicit));const i={client_id:e,redirect_uri:this.options.redirectUrl,authorization_endpoint:"https://oauth2.xumm.app/auth",token_endpoint:"https://oauth2.xumm.app/token",requested_scopes:"XummPkce",storage:this.options.storage,implicit:this.options.implicit};if(this.pkce=new a.default(i),this.options.rememberJwt){u("Remember JWT");try{const e=JSON.parse((null===(n=this.options.storage)||void 0===n?void 0:n.getItem("XummPkceJwt"))||"{}");if((null==e?void 0:e.jwt)&&"string"==typeof e.jwt){const t=new s.XummSdkJwt(e.jwt);this.ping=t.ping(),this.ping.then((n=>r(this,void 0,void 0,(function*(){var r;(null===(r=null==n?void 0:n.jwtData)||void 0===r?void 0:r.sub)?(this.autoResolvedFlow=Object.assign(e,{sdk:t}),yield this.authorize(),this.emit("retrieved")):this.logout()})))).catch((e=>{this.logout()}))}else this.logout()}catch(e){}}window.addEventListener("message",(e=>{var t;if(u("Received Event from ",e.origin),"{"===String((null==e?void 0:e.data)||"").slice(0,1)&&"}"===String((null==e?void 0:e.data)||"").slice(-1)&&(u("Got PostMessage with JSON"),"https://xumm.app"===e.origin||"https://oauth2.xumm.app"===e.origin)){u("Got PostMessage from https://xumm.app / https://oauth2.xumm.app");try{const n=JSON.parse(e.data);"xumm_sign_request"===(null==n?void 0:n.source)&&(null==n?void 0:n.payload)?u("Payload opened:",n.payload):"xumm_sign_request_resolved"===(null==n?void 0:n.source)&&(null==n?void 0:n.options)?(u("Payload resolved, mostmessage containing options containing redirect URL: ",n),this.resolved=!0,this.pkce.exchangeForAccessToken(n.options.full_redirect_uri).then((e=>{if(this.jwt=e.access_token,null==e?void 0:e.error_description)throw new Error(null==e?void 0:e.error_description);fetch("https://oauth2.xumm.app/userinfo",{headers:{Authorization:"Bearer "+e.access_token}}).then((e=>e.json())).then((t=>{var n;if(this.resolvePromise){if(this.options.rememberJwt){u("Remembering JWT");try{null===(n=this.options.storage)||void 0===n||n.setItem("XummPkceJwt",JSON.stringify({jwt:e.access_token,me:t}))}catch(e){u("Could not persist JWT to local storage",e)}}this.resolvePromise({jwt:e.access_token,sdk:new s.XummSdkJwt(e.access_token),me:t})}}))})).catch((e=>{this.rejectPromise&&this.rejectPromise((null==e?void 0:e.error)?new Error(e.error):e),u((null==e?void 0:e.error)||e)}))):"xumm_sign_request_rejected"===(null==n?void 0:n.source)?(u("Payload rejected",null==n?void 0:n.options),this.rejectPromise&&this.rejectPromise(new Error((null===(t=null==n?void 0:n.options)||void 0===t?void 0:t.error_description)||"Payload rejected"))):"xumm_sign_request_popup_closed"===(null==n?void 0:n.source)?(u("Popup closed, wait 750ms"),setTimeout((()=>{!this.resolved&&this.rejectPromise&&this.rejectPromise(new Error("Sign In window closed"))}),750)):u("Unexpected message, skipping",null==n?void 0:n.source)}catch(e){u("Error parsing message",(null==e?void 0:e.message)||e)}}}),!1);const l=new URLSearchParams((null===(o=null===document||void 0===document?void 0:document.location)||void 0===o?void 0:o.search)||"");if(l.get("authorization_code")||l.get("access_token")||l.get("error_description")){this.mobileRedirectFlow=!0,this.urlParams=l;let e=!1;const t=t=>r(this,void 0,void 0,(function*(){u("onDocumentReady",document.readyState),e||"complete"!==document.readyState||(e=!0,u("(readystatechange: [ "+document.readyState+" ])"),this.handleMobileGrant(),yield this.authorize(),this.emit("retrieved"))}));t(),document.addEventListener("readystatechange",t)}}emit(e,...t){return this.eventPromises[e].promise.then((()=>super.emit(e,...t))),!0}on(e,t){return this.eventPromises[e].resolve(),super.on(e,t)}off(e,t){return this.eventPromises[e]=c(),super.off(e,t)}authorizeUrl(){return this.pkce.authorizeUrl()}handleMobileGrant(){if(this.urlParams&&this.mobileRedirectFlow){const e={data:JSON.stringify(this.urlParams.get("authorization_code")||this.urlParams.get("access_token")?{source:"xumm_sign_request_resolved",options:{full_redirect_uri:document.location.href}}:{source:"xumm_sign_request_rejected",options:{error:this.urlParams.get("error"),error_code:this.urlParams.get("error_code"),error_description:this.urlParams.get("error_description")}}),origin:"https://oauth2.xumm.app"},t=new MessageEvent("message",e);return window.dispatchEvent(t),!0}return!1}authorize(){return r(this,void 0,void 0,(function*(){if(this.resolvedSuccessfully)return this.promise;if(this.resolved=!1,yield this.ping,!this.mobileRedirectFlow&&!this.autoResolvedFlow){const e=this.authorizeUrl(),t=window.open(e,"XummPkceLogin","directories=no,titlebar=no,toolbar=no,location=no,status=no,menubar=no,scrollbars=no,resizable=no,width=600,height=790");this.popup=t,u("Popup opened...",e)}this.resolved=!1;return(()=>{var e;const t=new URLSearchParams((null===(e=null===document||void 0===document?void 0:document.location)||void 0===e?void 0:e.search)||"");t.delete("authorization_code"),t.delete("code"),t.delete("scope"),t.delete("state"),t.delete("access_token"),t.delete("refresh_token"),t.delete("token_type"),t.delete("expires_in");const n=t.toString(),r=document.location.href.split("?")[0]+(""!==n?"?":"")+n;window.history.replaceState({path:r},"",r)})(),this.autoResolvedFlow?this.resolved||(this.resolved=!0,this.promise=Promise.resolve(this.autoResolvedFlow),this.rejectPromise=this.resolvePromise=()=>{},u("Auto resolved"),this.emit("success")):this.promise=new Promise(((e,t)=>{this.resolvePromise=t=>{const n=e(t);return this.resolved=!0,this.resolvedSuccessfully=!0,u("Xumm Sign in RESOLVED"),this.emit("success"),n},this.rejectPromise=e=>{const n=t(e);return this.resolved=!0,this.emit("error","string"==typeof e?new Error(e):e),u("Xumm Sign in REJECTED"),n}})),this.promise}))}state(){return r(this,void 0,void 0,(function*(){return this.promise}))}logout(){var e;setTimeout((()=>this.emit("loggedout")),0);try{this.resolved=!1,this.resolvedSuccessfully=void 0,this.autoResolvedFlow=void 0,null===(e=this.options.storage)||void 0===e||e.removeItem("XummPkceJwt"),this.mobileRedirectFlow=!1}catch(e){}}getPopup(){return null==this?void 0:this.popup}}n.XummPkceThread=l;const d=e=>{let t=!1;e&&"object"==typeof window&&void 0===window._XummPkce&&(window._XummPkce=e,t=!0);const n=null===window||void 0===window?void 0:window._XummPkce;return n&&t&&u("XummPkce attached to window"),n};n.XummPkce=class{constructor(e,t){"undefined"!=typeof window&&"undefined"!=typeof document&&(d()||d(new l(e,t)))}on(e,t){const n=d();if(n)return n.on(e,t),this}off(e,t){const n=d();if(n)return n.off(e,t),this}authorize(){const e=d();if(e)return e.authorize()}state(){const e=d();if(e)return e.state()}logout(){const e=d();if(e)return e.logout()}}},{events:2,"xumm-js-pkce":17,"xumm-sdk":24}],19:[function(e,t,n){"use strict";var r=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))};Object.defineProperty(n,"__esModule",{value:!0}),n.JwtUserdata=void 0;const o=e("debug"),i=e("./utils"),s=o.debug("xumm-sdk:xapp:userdata");n.JwtUserdata=class{constructor(e){s("Constructed"),this.Meta=e}list(){return r(this,void 0,void 0,(function*(){const e=yield this.Meta.call("userdata","GET");return i.throwIfError(e),e.keys}))}get(e){var t;return r(this,void 0,void 0,(function*(){const n=Array.isArray(e)?e.join(","):e,r=yield this.Meta.call("userdata/"+n,"GET");return i.throwIfError(r),n.split(",").length>1?r.data:(null===(t=r.data)||void 0===t?void 0:t[n])||{}}))}delete(e){return r(this,void 0,void 0,(function*(){const t=yield this.Meta.call("userdata/"+e,"DELETE");return i.throwIfError(t),t.persisted}))}set(e,t){return r(this,void 0,void 0,(function*(){const n=yield this.Meta.call("userdata/"+e,"POST",t);return i.throwIfError(n),n.persisted}))}}},{"./utils":25,debug:7}],20:[function(e,t,n){"use strict";var r=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))},o=this&&this.__importDefault||function(e){return e&&e.__esModule?e:{default:e}};Object.defineProperty(n,"__esModule",{value:!0}),n.Meta=void 0;const i=e("debug"),s=o(e("fetch-ponyfill")),{fetch:a,Request:u,Response:c,Headers:l}=s.default(),d=e("os-browserify"),h=e("./utils"),f=e("./index"),p=i.debug("xumm-sdk:meta");n.Meta=class{constructor(e,t){this.isBrowser=!1,this.jwtFlow=!1,this.injected=!1,this.endpoint="https://xumm.app",p("Constructed");const n=new RegExp("^[a-f0-9]{8}-[a-f0-9]{4}-[a-f0-9]{4}-[a-f0-9]{4}-[a-f0-9]{12}$"),r={split:t.split(":"),uuidv4:""};if(3===r.split.length&&"xApp:OneTimeToken"===r.split.slice(0,2).join(":")?(r.uuidv4=r.split[2],this.jwtFlow=!0):r.split.length>1&&"RAWJWT"===r.split[0]?(this.jwtFlow=!0,this.jwt=r.split.slice(1).join(":")):r.uuidv4=t,!n.test(e)||!n.test(r.uuidv4)){if(!this.jwtFlow)throw new Error("Invalid API Key and/or API Secret. Use dotenv or constructor params.");if(!this.jwt)throw new Error("Invalid API Key and/or OTT (One Time Token). Provide OTT param (2nd param) or make sure `xAppToken` query param is present (Browser)")}return"undefined"!=typeof globalThis&&Object.keys(globalThis).indexOf("window")<0?p("Running in node"):(console.log("XUMM SDK: Running in browser"),this.isBrowser=!0),this.apiKey=e,this.apiSecret=r.uuidv4,this.jwtFlow&&!this.jwt&&(this.authPromise=new Promise((e=>{this.authPromiseResolve=e})),Promise.resolve().then((()=>this.authorize())).catch((e=>{p("Authorize error:",e.message),(null==this?void 0:this.invoker)&&this.invoker.caught(e),this.authPromiseResolve&&this.authPromiseResolve()}))),this}setEndpoint(e){return!!e.match(/^http/)&&(this.endpoint=e.trim(),!0)}authorize(){var e,t,n,o;return r(this,void 0,void 0,(function*(){let r;p("JWT Authorize",this.apiSecret),(null==this?void 0:this.invoker)&&this.invoker.constructor===f.XummSdkJwt&&(r=this.invoker._jwtStore(this,(e=>this.jwt=e)));const i=(null==r?void 0:r.get(this.apiSecret))||(yield this.call("authorize"));if(null===(t=null===(e=i)||void 0===e?void 0:e.error)||void 0===t?void 0:t.code)p("Could not resolve API Key & OTT to JWT (already fetched? Unauthorized?)"),(null==this?void 0:this.invoker)&&this.invoker.constructor===f.XummSdkJwt&&(null===(n=null==this?void 0:this.invoker)||void 0===n?void 0:n.fatalHandler)?this.invoker.fatalHandler(new Error(i.error.reference)):h.throwIfError(i);else{if(!(null===(o=i)||void 0===o?void 0:o.jwt))throw new Error("Unexpected response for xApp JWT authorize request");{const e=i;null==r||r.set(this.apiSecret,e)}}this.authPromiseResolve&&this.authPromiseResolve()}))}call(e,t="GET",n){var o;return r(this,void 0,void 0,(function*(){const r=t.toUpperCase(),i=e.split("/")[0];this.jwtFlow&&!(null==this?void 0:this.jwt)&&this.authPromise&&"authorize"!==e&&(yield this.authPromise);try{let t;void 0!==n&&("object"==typeof n&&null!==n&&(t=JSON.stringify(n)),"string"==typeof n&&(t=n));const o={"Content-Type":"application/json"};this.isBrowser||Object.assign(o,{"User-Agent":`xumm-sdk/node (${d.hostname()}) node-fetch`}),this.jwtFlow?"authorize"===e?Object.assign(o,{"x-api-key":this.apiKey,"x-api-ott":this.apiSecret}):Object.assign(o,{Authorization:"Bearer "+this.jwt}):Object.assign(o,{"x-api-key":this.apiKey,"x-api-secret":this.apiSecret});const s=["authorize","ping","curated-assets","rates","payload","userdata","xrpl-tx","nftoken-detail"],u=this.jwtFlow&&s.indexOf(i)>-1?"jwt":"platform",c=yield a(this.endpoint+"/api/v1/"+u+"/"+e,{method:r,body:t,headers:o});return yield c.json()}catch(e){const t=new Error(`Unexpected response from XUMM API [${r}:${i}]`);throw t.stack=(null===(o=e)||void 0===o?void 0:o.stack)||void 0,t}}))}ping(){var e,t;return r(this,void 0,void 0,(function*(){const n=yield this.call("ping");if(h.throwIfError(n),void 0!==n.auth)return n.auth;if(void 0!==(null===(e=n)||void 0===e?void 0:e.ott_uuidv4))return{application:{uuidv4:n.app_uuidv4,name:n.app_name},jwtData:n};if(void 0!==(null===(t=n)||void 0===t?void 0:t.usertoken_uuidv4))return{application:{uuidv4:n.client_id,name:n.app_name},jwtData:n};throw new Error("Unexpected response for ping request")}))}getCuratedAssets(){return r(this,void 0,void 0,(function*(){return yield this.call("curated-assets")}))}getRates(e){return r(this,void 0,void 0,(function*(){return yield this.call("rates/"+e.trim().toUpperCase())}))}getKycStatus(e){return r(this,void 0,void 0,(function*(){if(e.trim().match(/^r/)){const t=yield this.call("kyc-status/"+e.trim());return(null==t?void 0:t.kycApproved)?"SUCCESSFUL":"NONE"}{const t=yield this.call("kyc-status","POST",{user_token:e});return(null==t?void 0:t.kycStatus)||"NONE"}}))}getTransaction(e){return r(this,void 0,void 0,(function*(){return yield this.call("xrpl-tx/"+e.trim())}))}getNftokenDetail(e){return r(this,void 0,void 0,(function*(){if(!this.jwtFlow)throw new Error("getNftokenDetail: only available in JWT (XummSdkJwt) mode");return yield this.call("nftoken-detail/"+e.trim())}))}verifyUserTokens(e){return r(this,void 0,void 0,(function*(){return(yield this.call("user-tokens","POST",{tokens:Array.isArray(e)?e:[e]})).tokens}))}_inject(e){if(this.injected)throw new Error("Cannot `_inject` twice");this.invoker=e}}},{"./index":24,"./utils":25,debug:7,"fetch-ponyfill":10,"os-browserify":12}],21:[function(e,t,n){"use strict";var r=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))};Object.defineProperty(n,"__esModule",{value:!0}),n.Payload=void 0;const o=e("debug"),i=e("websocket"),s=e("./utils"),a=o.debug("xumm-sdk:payload"),u=o.debug("xumm-sdk:payload:websocket");n.Payload=class{constructor(e){a("Constructed"),this.Meta=e}resolvePayload(e){var t,n,o;return r(this,void 0,void 0,(function*(){if("string"==typeof e)return yield this.get(e,!0);if(void 0!==(null===(t=e)||void 0===t?void 0:t.uuid))return yield this.get(e.uuid,!0);if(void 0!==(null===(o=null===(n=e)||void 0===n?void 0:n.meta)||void 0===o?void 0:o.uuid))return e;throw new Error("Could not resolve payload (not found)")}))}create(e,t=!1){var n;return r(this,void 0,void 0,(function*(){const r=void 0!==e.TransactionType&&void 0===e.txjson,o=yield this.Meta.call("payload","POST",r?{txjson:e}:e);t&&s.throwIfError(o);return void 0!==(null===(n=o)||void 0===n?void 0:n.next)?o:null}))}get(e,t=!1){var n,o;return r(this,void 0,void 0,(function*(){const r="string"==typeof e?e:null==e?void 0:e.uuid,i=yield this.Meta.call("payload/"+r,"GET");t&&s.throwIfError(i);return void 0!==(null===(o=null===(n=i)||void 0===n?void 0:n.meta)||void 0===o?void 0:o.uuid)?i:null}))}subscribe(e,t){var n,o;return r(this,void 0,void 0,(function*(){const a=new s.DeferredPromise,c=yield this.resolvePayload(e);if(c){const e="undefined",s=typeof(null===(n=globalThis)||void 0===n?void 0:n.MockedWebSocket)!==e&&typeof jest!==e?new(null===(o=globalThis)||void 0===o?void 0:o.MockedWebSocket)("ws://xumm.local"):new i.w3cwebsocket(this.Meta.endpoint.replace(/^http/,"ws")+"/sign/"+c.meta.uuid);return a.promise.then((()=>{s.close()})),s.onopen=()=>{u(`Payload ${c.meta.uuid}: Subscription active (WebSocket opened)`)},s.onmessage=e=>r(this,void 0,void 0,(function*(){const n=e.data;let o;try{o=JSON.parse(n.toString())}catch(e){u(`Payload ${c.meta.uuid}: Received message, unable to parse as JSON`,e)}if(o&&t&&void 0===o.devapp_fetched)try{const e=yield t({uuid:c.meta.uuid,data:o,resolve(e){return r(this,void 0,void 0,(function*(){yield a.resolve(e||void 0)}))},payload:c});void 0!==e&&a.resolve(e)}catch(e){u(`Payload ${c.meta.uuid}: Callback exception`,e)}})),s.onclose=e=>{u(`Payload ${c.meta.uuid}: Subscription ended (WebSocket closed)`)},{payload:c,resolve(e){a.resolve(e||void 0)},resolved:a.promise,websocket:s}}throw s.throwIfError(c),Error("Couldn't subscribe: couldn't fetch payload")}))}cancel(e,t=!1){var n,o,i;return r(this,void 0,void 0,(function*(){const r=yield this.resolvePayload(e),a=yield this.Meta.call("payload/"+(null===(n=null==r?void 0:r.meta)||void 0===n?void 0:n.uuid),"DELETE");t&&s.throwIfError(a);return void 0!==(null===(i=null===(o=a)||void 0===o?void 0:o.meta)||void 0===i?void 0:i.uuid)?a:null}))}createAndSubscribe(e,t){return r(this,void 0,void 0,(function*(){const n=yield this.create(e,!0);if(n){const e=yield this.subscribe(n,t);return Object.assign({created:n},e)}throw new Error("Error creating payload or subscribing to created payload")}))}}},{"./utils":25,debug:7,websocket:14}],22:[function(e,t,n){"use strict";var r=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))};Object.defineProperty(n,"__esModule",{value:!0}),n.Push=void 0;const o=e("debug"),i=e("./JwtUserdata"),s=e("./utils"),a=o.debug("xumm-sdk:xapp");n.Push=class{constructor(e){a("Constructed"),this.Meta=e,this.userdata=new i.JwtUserdata(e)}event(e){return r(this,void 0,void 0,(function*(){const t=yield this.Meta.call("xapp/event","POST",e);return s.throwIfError(t),t}))}notification(e){return r(this,void 0,void 0,(function*(){const t=yield this.Meta.call("xapp/push","POST",e);return s.throwIfError(t),t}))}}},{"./JwtUserdata":19,"./utils":25,debug:7}],23:[function(e,t,n){"use strict";var r=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))};Object.defineProperty(n,"__esModule",{value:!0}),n.Storage=void 0;const o=e("debug"),i=e("./utils"),s=o.debug("xumm-sdk:storage");n.Storage=class{constructor(e){s("Constructed"),this.Meta=e}get(){return r(this,void 0,void 0,(function*(){const e=yield this.Meta.call("app-storage","GET");return i.throwIfError(e),e.data}))}set(e){return r(this,void 0,void 0,(function*(){const t=yield this.Meta.call("app-storage","POST",e);return i.throwIfError(t),t.stored}))}delete(){return r(this,void 0,void 0,(function*(){const e=yield this.Meta.call("app-storage","DELETE");return i.throwIfError(e),e.stored}))}}},{"./utils":25,debug:7}],24:[function(e,t,n){(function(t){(function(){"use strict";var r=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))};Object.defineProperty(n,"__esModule",{value:!0}),n.XummSdkJwt=n.XummSdk=void 0;const o=e("debug"),i=e("./Meta"),s=e("./Storage"),a=e("./Payload"),u=e("./xApp"),c=e("./Push"),l=e("./JwtUserdata"),d=o.debug("xumm-sdk");class h{constructor(e,t){return d("Constructed"),this.Meta=new i.Meta(e||this.getEnv("XUMM_APIKEY"),t||this.getEnv("XUMM_APISECRET")),this.storage=new s.Storage(this.Meta),this.payload=new a.Payload(this.Meta),this.jwtUserdata=new l.JwtUserdata(this.Meta),this.Push=new c.Push(this.Meta),this.xApp=new u.xApp(this.Meta),this.Meta._inject(this),this}getEnv(e){let n="";try{n="undefined"!=typeof Deno&&Deno.env.get(e)||"",n=(null==t?void 0:t.env[e])||""}catch(e){}return n}ping(){return this.Meta.ping()}getCuratedAssets(){return this.Meta.getCuratedAssets()}getRates(e){return this.Meta.getRates(e)}getKycStatus(e){return this.Meta.getKycStatus(e)}getTransaction(e){return this.Meta.getTransaction(e)}getNftokenDetail(e){return this.Meta.getNftokenDetail(e)}verifyUserTokens(e){return this.Meta.verifyUserTokens(e)}verifyUserToken(e){return r(this,void 0,void 0,(function*(){const t=yield this.Meta.verifyUserTokens([e]);return Array.isArray(t)&&1===t.length?t[0]:null}))}setEndpoint(e){return this.Meta.setEndpoint(e)}caught(e){throw e}}n.XummSdk=h;n.XummSdkJwt=class extends h{constructor(e,t,n){var r,o,i,s,a,u,c,l;let h=String(t||"").trim().toLowerCase();const f=36!==e.length;if(!f&&void 0===t&&"undefined"!=typeof window&&void 0!==window.URLSearchParams){const e=new window.URLSearchParams((null===(r=null===window||void 0===window?void 0:window.location)||void 0===r?void 0:r.search)||"");for(const t of e.entries())"xAppToken"===t[0]&&(h=t[1].toLowerCase().trim());if(""===h&&!(null==n?void 0:n.store)&&!(null==n?void 0:n.noAutoRetrieve)&&"string"==typeof(null===(o=null===window||void 0===window?void 0:window.localStorage)||void 0===o?void 0:o.XummSdkJwt))try{const e=null===(s=null===(i=null===window||void 0===window?void 0:window.localStorage)||void 0===i?void 0:i.XummSdkJwt)||void 0===s?void 0:s.split(":"),t=JSON.parse(null===(a=null==e?void 0:e.slice(1))||void 0===a?void 0:a.join(":"));if(null==t?void 0:t.jwt){const n=JSON.parse(atob(null===(u=t.jwt.split("."))||void 0===u?void 0:u[1]));if(null==n?void 0:n.exp){const t=(null==n?void 0:n.exp)-Math.floor((new Date).getTime()/1e3);console.log("Restoring OTT "+(null==e?void 0:e[0])),t>3600?h=null==e?void 0:e[0]:console.log("Skip restore: not valid for one more hour")}}}catch(e){console.log("JWT Restore Error",e)}}super(e,f||""===h?"RAWJWT:"+e:"xApp:OneTimeToken:"+h),this.resolve=e=>{d("OTT data resolved",e)},this.reject=e=>{d("OTT data rejected",e.message)},this.ottResolved=f?Promise.resolve():new Promise(((e,t)=>{this.resolve=e,this.reject=t})),(null==n?void 0:n.fatalHandler)&&(this.fatalHandler=n.fatalHandler),this.store={get(e){var t;if(d("[JwtStore] » Builtin JWT store GET"),"undefined"!=typeof window&&void 0!==window.localStorage&&"string"==typeof window.localStorage.XummSdkJwt){const n=window.localStorage.XummSdkJwt.split(":");if(n[0]===e){d("Restoring OTT from localStorage:",e);try{return JSON.parse(n.slice(1).join(":"))}catch(e){d("Error restoring OTT Data (JWT) from localStorage",null===(t=e)||void 0===t?void 0:t.message)}}}},set(e,t){d("[JwtStore] » Builtin JWT store SET",e),"undefined"!=typeof window&&"undefined"!=typeof localStorage&&(window.localStorage.XummSdkJwt=e+":"+JSON.stringify(t))}},(null===(c=null==n?void 0:n.store)||void 0===c?void 0:c.get)&&(this.store.get=n.store.get),(null===(l=null==n?void 0:n.store)||void 0===l?void 0:l.set)&&(this.store.set=n.store.set),f?(this.reject(new Error("Not in OTT flow: in raw JWT (OAuth2-like) flow")),d("Using JWT (Raw, OAuth2) flow")):d("Using JWT (xApp) flow")}_jwtStore(e,t){if(e&&(null==e?void 0:e.constructor)===i.Meta)return{get:e=>{var t;return d("[JwtStore] Proxy GET"),null===(t=this.store)||void 0===t?void 0:t.get(e)},set:(e,n)=>{var r;return d("[JwtStore] Proxy SET"),this.resolve(n.ott),t(n.jwt),this.jwt=n.jwt,null===(r=this.store)||void 0===r?void 0:r.set(e,n)}};throw new Error("Invalid _jwtStore invoker")}getOttData(){return r(this,void 0,void 0,(function*(){const e=yield this.ottResolved;if(e)return e;throw new Error("Called getOttData on a non OTT-JWT flow")}))}getJwt(){return r(this,void 0,void 0,(function*(){return yield this.ottResolved,this.jwt}))}caught(e){this.reject(e)}}}).call(this)}).call(this,e("_process"))},{"./JwtUserdata":19,"./Meta":20,"./Payload":21,"./Push":22,"./Storage":23,"./xApp":26,_process:13,debug:7}],25:[function(e,t,n){"use strict";Object.defineProperty(n,"__esModule",{value:!0}),n.DeferredPromise=n.throwIfError=void 0,n.throwIfError=function(e){var t,n,r,o,i,s;if(void 0!==e.message)throw new Error(e.message);if(void 0===e.next&&void 0===(null===(n=null===(t=e)||void 0===t?void 0:t.meta)||void 0===n?void 0:n.uuid)&&void 0===(null===(o=null===(r=e)||void 0===r?void 0:r.application)||void 0===o?void 0:o.uuidv4)&&void 0!==(null===(s=null===(i=e)||void 0===i?void 0:i.error)||void 0===s?void 0:s.code)){const t=e.error;throw new Error(`Error code ${t.code}, see XUMM Dev Console, reference: ${t.reference}`)}};n.DeferredPromise=class{constructor(){this.resolveFn=e=>{},this.rejectFn=e=>{},this.promise=new Promise(((e,t)=>{this.resolveFn=e,this.rejectFn=t}))}resolve(e){return this.resolveFn(e),this.promise}reject(e){return this.rejectFn(e),this.promise}}},{}],26:[function(e,t,n){"use strict";var r=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))};Object.defineProperty(n,"__esModule",{value:!0}),n.xApp=void 0;const o=e("debug"),i=e("./JwtUserdata"),s=e("./utils"),a=o.debug("xumm-sdk:xapp");n.xApp=class{constructor(e){a("Constructed"),this.Meta=e,this.userdata=new i.JwtUserdata(e)}get(e){return r(this,void 0,void 0,(function*(){const t=yield this.Meta.call("xapp/ott/"+e,"GET");return s.throwIfError(t),t}))}}},{"./JwtUserdata":19,"./utils":25,debug:7}],27:[function(e,t,n){"use strict";var r,o=this&&this.__createBinding||(Object.create?function(e,t,n,r){void 0===r&&(r=n);var o=Object.getOwnPropertyDescriptor(t,n);o&&!("get"in o?!t.__esModule:o.writable||o.configurable)||(o={enumerable:!0,get:function(){return t[n]}}),Object.defineProperty(e,r,o)}:function(e,t,n,r){void 0===r&&(r=n),e[r]=t[n]}),i=this&&this.__exportStar||function(e,t){for(var n in e)"default"===n||Object.prototype.hasOwnProperty.call(t,n)||o(t,e,n)},s=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))};Object.defineProperty(n,"__esModule",{value:!0}),n.xApp=void 0;const a=e("events"),u=e("./types");i(e("./types"),n);const c=.25,l=Number(new Date);let d;const h=new Promise((e=>{d=t=>{console.log("Doc Ready...");const n=(Number(new Date)-l)/1e3;n<c?(console.log("Doc not alive >= 0.25 sec, stalling for "+(c-n)),setTimeout((function(){e(t)}),1e3*(c-n))):(console.log("Doc alive 0.25+ sec, go ahead"),e(t))}}));h.then((()=>{console.log("documentReadyPromise resolved")})).catch((e=>{console.log(e)})),"undefined"!=typeof document&&document.addEventListener("readystatechange",(e=>{console.log("(readystatechange: [ "+document.readyState+" ])"),"complete"===document.readyState&&d()})),"undefined"!=typeof window&&console.log("Loading xApp SDK");let f="undefined"!=typeof window?window:{},p=!1;(null==f?void 0:f.parent)&&(null===(r=f.parent)||void 0===r||r.postMessage("XAPP_PROXY_INIT","*"));const v=(e,t,n=0)=>s(void 0,void 0,void 0,(function*(){var r,o;if(yield h,void 0!==(null==f?void 0:f.ReactNativeWebView)||p){const n=(Number(new Date)-l)/1e3;if(["close"].indexOf(e)>-1){const e=4;n<e&&(console.log("xApp close, doc alive < minAliveTimeSec, stall: "+(e-n)),yield new Promise((t=>{setTimeout((()=>{t(!0)}),1e3*(e-n))})))}const i=JSON.stringify(Object.assign({command:e},t||{}));return p?null===(r=f.parent)||void 0===r||r.postMessage(i,"*"):null===(o=f.ReactNativeWebView)||void 0===o||o.postMessage(i),console.log("xAppActionAttempt Success",e,t),!0}return 250*n<2e3?(console.log("xAppActionAttempt Attempt "+n+" » Retry",e,t),yield new Promise((e=>{setTimeout(e,250)})),v(e,t,n+1)):(console.log("xAppActionAttempt Failed after attempt "+n,e,t),new Error("xApp."+e.replace(/^xApp/,"")+": could not contact Xumm App Host"))}));class m extends a.EventEmitter{constructor(){super(),"complete"===document.readyState&&d();const e=e=>{const t=e;if("string"==typeof(null==t?void 0:t.data)&&"XAPP_PROXY_INIT_ACK"===t.data)return console.log("xApp Proxy ACK received, switching to PROXY (SANDBOX) mode"),void(p=!0);try{const e=JSON.parse((null==t?void 0:t.data)||"{}");if(console.log({_event:e}),"object"==typeof e&&null!==e)if("string"==typeof e.method&&e.method in u.xAppEvents){console.log("xApp Event received",e.method,e);const t=e.method;switch(delete e.method,t){case String(u.xAppEvents.payloadResolved):this.emit("payload",e);break;case String(u.xAppEvents.scanQr):this.emit("qr",e);break;case String(u.xAppEvents.selectDestination):this.emit("destination",e)}}else console.log("xApp Event received, not in xAppEvents",e.method,u.xAppEvents)}catch(e){const t=(null==e?void 0:e.message)||"";t.match(/XAPP_PROXY_INIT/)||console.log("xApp Event received, cannot parse as JSON",t)}};"function"==typeof window.addEventListener&&window.addEventListener("message",e),"function"==typeof document.addEventListener&&document.addEventListener("message",e)}navigate(e){return"string"!=typeof(null==e?void 0:e.xApp)?Promise.reject(new Error("xApp.navigate: Invalid argument: `xApp`")):v("xAppNavigate",e)}openSignRequest(e){return"string"!=typeof(null==e?void 0:e.uuid)?Promise.reject(new Error("xApp.openSignRequest: Invalid argument: `uuid`")):e.uuid.match(/^[0-9A-F]{8}-[0-9A-F]{4}-4[0-9A-F]{3}-[89AB][0-9A-F]{3}-[0-9A-F]{12}$/i)?v("openSignRequest",e):Promise.reject(new Error("xApp.openSignRequest: Invalid payload UUID"))}selectDestination(){return v("selectDestination")}openBrowser(e){return"string"!=typeof(null==e?void 0:e.url)?Promise.reject(new Error("xApp.openBrowser: Invalid argument: `url`")):v("openBrowser",e)}share(e){return"string"!=typeof(null==e?void 0:e.text)?Promise.reject(new Error("xApp.share: Invalid argument: `text`")):v("share",e)}scanQr(){return v("scanQr")}tx(e){return"string"!=typeof(null==e?void 0:e.tx)?Promise.reject(new Error("xApp.tx: Invalid argument: `tx`")):"string"!=typeof(null==e?void 0:e.account)?Promise.reject(new Error("xApp.tx: Invalid argument: `account`")):v("txDetails",e)}close(e){return v("close",e)}ready(){return v("ready")}customCommand(e,t){return v(e,t)}}const y=e=>{let t=!1;e&&"object"==typeof f&&void 0===f._xAppSdk&&(f._xAppSdk=e,t=!0);const n=null==f?void 0:f._xAppSdk;return n&&t&&console.log("xAppSdk attached to window"),n};n.xApp=class{constructor(){"undefined"!=typeof window&&"undefined"!=typeof document&&(y()||y(new m))}on(e,t){const n=y();if(n)return n.on(e,t),this}off(e,t){const n=y();if(n)return n.off(e,t),this}navigate(e){const t=y();if(t)return t.navigate(e)}openSignRequest(e){const t=y();if(t&&(null==e?void 0:e.uuid))return t.openSignRequest(e)}selectDestination(){const e=y();if(e)return e.selectDestination()}openBrowser(e){const t=y();if(t)return t.openBrowser(e)}share(e){const t=y();if(t)return t.share(e)}scanQr(){const e=y();if(e)return e.scanQr()}tx(e){const t=y();if(t)return t.tx(e)}close(e){const t=y();if(t)return t.close(e)}ready(){const e=y();if(e)return e.ready()}customCommand(e,t){const n=y();if(n)return n.customCommand(e,t)}}},{"./types":28,events:2}],28:[function(e,t,n){"use strict";Object.defineProperty(n,"__esModule",{value:!0}),n.xAppEvents=void 0,function(e){e.scanQr="scanQr",e.payloadResolved="payloadResolved",e.selectDestination="selectDestination"}(n.xAppEvents||(n.xAppEvents={}))},{}],Xumm:[function(e,t,n){(function(r){(function(){"use strict";var o=this&&this.__awaiter||function(e,t,n,r){return new(n||(n=Promise))((function(o,i){function s(e){try{u(r.next(e))}catch(e){i(e)}}function a(e){try{u(r.throw(e))}catch(e){i(e)}}function u(e){var t;e.done?o(e.value):(t=e.value,t instanceof n?t:new n((function(e){e(t)}))).then(s,a)}u((r=r.apply(e,t||[])).next())}))};Object.defineProperty(n,"__esModule",{value:!0}),n.Xumm=void 0;const i=e("xumm-oauth2-pkce"),s=e("events");var a;!function(e){e.cli="cli",e.browser="browser",e.xapp="xapp"}(a||(a={}));const u={cli:!1,browser:!1,xapp:!1},c=new RegExp("^[0-9(a-f|A-F)]{8}-[0-9(a-f|A-F)]{4}-4[0-9(a-f|A-F)]{3}-[89ab][0-9(a-f|A-F)]{3}-[0-9(a-f|A-F)]{12}$"),l={},d="object"==typeof r&&r&&(null==r?void 0:r.env)||{};Object.assign(u,{cli:Object.keys(d).indexOf("NODE")>-1||Object.keys(d).indexOf("SHELL")>-1||Object.keys(d).indexOf("TERM")>-1||Object.keys(d).indexOf("PATH")>-1}),Object.assign(u,{browser:"object"==typeof r&&r&&(null==r?void 0:r.browser)||"object"==typeof document&&document&&(null===document||void 0===document?void 0:document.location)}),Object.assign(u,{xapp:u.browser&&!!navigator.userAgent.match(/xumm\/xapp/i)});const h=Object.keys(u).filter((e=>u[e])),f=[],p=e=>o(void 0,void 0,void 0,(function*(){return yield Promise.all(f),yield e()})),v=e=>new Proxy(e,{get:(e,t)=>["on","off"].indexOf(String(t))<0&&("function"==typeof e[t]||"Promise"===e.constructor.name)?function(){return"Promise"===e.constructor.name?e.then((e=>p((()=>e[t](...arguments))))):p((()=>e[t](...arguments)))}:e[t]}),m={XummSdk:!1,XummSdkJwt:!1,XummPkce:!1,xApp:!1};let y,w="",g={},b={},_=0;class x{constructor(){this.account=p((()=>{var e,t,n;return null!==(t=null!==(e=null==g?void 0:g.sub)&&void 0!==e?e:null==b?void 0:b.sub)&&void 0!==t?t:null===(n=null==y?void 0:y.account_info)||void 0===n?void 0:n.account})),this.picture=p((()=>{var e,t,n,r,o,i,s;return null!==(e=null==b?void 0:b.picture)&&void 0!==e?e:(null!==(n=null!==(t=null==g?void 0:g.sub)&&void 0!==t?t:null==b?void 0:b.sub)&&void 0!==n?n:null===(r=null==y?void 0:y.account_info)||void 0===r?void 0:r.account)?`https://xumm.app/avatar/${null!==(i=null!==(o=null==g?void 0:g.sub)&&void 0!==o?o:null==b?void 0:b.sub)&&void 0!==i?i:null===(s=null==y?void 0:y.account_info)||void 0===s?void 0:s.account}.png`:void 0})),this.name=p((()=>{var e,t;return null!==(e=null==b?void 0:b.name)&&void 0!==e?e:null===(t=null==y?void 0:y.account_info)||void 0===t?void 0:t.name})),this.domain=p((()=>{var e,t;return null!==(e=null==b?void 0:b.domain)&&void 0!==e?e:null===(t=null==y?void 0:y.account_info)||void 0===t?void 0:t.domain})),this.source=p((()=>{var e,t;return null!==(e=null==b?void 0:b.source)&&void 0!==e?e:null===(t=null==y?void 0:y.account_info)||void 0===t?void 0:t.source})),this.networkType=p((()=>{var e,t;return null!==(t=null!==(e=null==b?void 0:b.networkType)&&void 0!==e?e:g.network_type)&&void 0!==t?t:null==y?void 0:y.nodetype})),this.networkEndpoint=p((()=>{var e,t;return null!==(t=null!==(e=null==b?void 0:b.networkEndpoint)&&void 0!==e?e:g.network_ndpoint)&&void 0!==t?t:null==y?void 0:y.nodewss})),this.blocked=p((()=>{var e,t;return null!==(e=null==b?void 0:b.blocked)&&void 0!==e?e:null===(t=null==y?void 0:y.account_info)||void 0===t?void 0:t.blocked})),this.kycApproved=p((()=>{var e,t;return null!==(e=null==b?void 0:b.kycApproved)&&void 0!==e?e:null===(t=null==y?void 0:y.account_info)||void 0===t?void 0:t.kycApproved})),this.proSubscription=p((()=>{var e,t;return null!==(e=null==b?void 0:b.proSubscription)&&void 0!==e?e:null===(t=null==y?void 0:y.account_info)||void 0===t?void 0:t.proSubscription})),this.profile=p((()=>{var e,t,n;return null!==(e=null==b?void 0:b.profile)&&void 0!==e?e:(null===(n=null===(t=null==y?void 0:y.account_info)||void 0===t?void 0:t.profile)||void 0===n?void 0:n.slug)?y.account_info.profile:void 0})),this.token=p((()=>{var e;return null!==(e=null==g?void 0:g.usertoken_uuidv4)&&void 0!==e?e:null}))}}class k extends s.EventEmitter{constructor(e,t){var n,r,o,i;super(),this.instance="0",this.jwtCredential=!1,this.runtime=u,this.apiKeyOrJwt="",this.apiKeyOrJwt=e,this.apiSecretOrOtt=t,_++,this.instance=String(_),void 0!==(null===console||void 0===console?void 0:console.log)&&(u.cli||console.log("Constructed Xumm",{runtime:h}));let s=!1;if("string"==typeof this.apiKeyOrJwt&&3===this.apiKeyOrJwt.split(".").length){let e;try{e=JSON.parse(atob(null===(n=this.apiKeyOrJwt.split("."))||void 0===n?void 0:n[1]))}catch(e){}if(Date.now()>=1e3*e.exp){s=!0;const t=null!==(i=null!==(o=null!==(r=null==e?void 0:e.app_uuidv4)&&void 0!==r?r:null==e?void 0:e.client_id)&&void 0!==o?o:null==e?void 0:e.aud)&&void 0!==i?i:"";if(this.apiKeyOrJwt=t,u.cli||console.log("JWT expired, falling back to API KEY: "+t),u.cli||u.xapp){const e=new Error("JWT Expired, cannot fall back to API credential: in CLI/xApp environment");throw this.emit("error",e),e}}s||(this.jwtCredential=!0,w=this.apiKeyOrJwt)}this.initialize(),this.user=new x,this.environment={jwt:p((()=>g)),ott:p((()=>y)),openid:p((()=>b)),bearer:p((()=>w)),ready:new Promise((e=>this.on("ready",(()=>e(void 0))))),success:new Promise((e=>this.on("success",(()=>e(void 0))))),retrieved:new Promise((e=>this.on("retrieved",(()=>e(void 0))))),retrieving:new Promise((e=>this.on("retrieving",(()=>e(void 0)))))},this.helpers=v(p((()=>l.XummSdk||l.XummSdkJwt))),this.push=v(p((()=>(l.XummSdk||l.XummSdkJwt).Push))),this.payload=v(p((()=>(l.XummSdk||l.XummSdkJwt).payload))),this.userstore=v(p((()=>(l.XummSdk||l.XummSdkJwt).jwtUserdata))),this.backendstore=v(p((()=>(l.XummSdk||l.XummSdkJwt).storage)));const a=null==l?void 0:l.xApp;a&&(this.xapp=a),setTimeout((()=>Promise.all([...f.filter((e=>"pkceRetrieverResolver"!==(null==e?void 0:e.promiseType))),u.xapp?Promise.resolve():new Promise((e=>{var t;(null==l?void 0:l.XummPkce)?(this.user.account.then((()=>e())),null===(t=l.XummPkce)||void 0===t||t.on("loggedout",(()=>e()))):e()}))]).then((()=>this.emit("ready")))),0)}initialize(){y=void 0,w="",g={},b={},m.XummSdkJwt=!1;const t=()=>o(this,void 0,void 0,(function*(){(null==l?void 0:l.xApp)&&(m.xApp=!0,l.xApp.on("qr",(e=>{this.emit("qr",e,this.instance)})),l.xApp.on("payload",(e=>{this.emit("payload",e,this.instance)})),l.xApp.on("destination",(e=>{this.emit("destination",e,this.instance)})))}));this.handlePkceEvents();const n=()=>o(this,void 0,void 0,(function*(){var e;if((null==l?void 0:l.XummSdkJwt)&&!m.XummSdkJwt){m.XummSdkJwt=!0;const t=this.jwtCredential||""!==w;t||(f.push(l.XummSdkJwt.getOttData()),f.push(l.XummSdkJwt.getJwt()));const n=t?null:yield l.XummSdkJwt.getOttData(),r=t?w:yield l.XummSdkJwt.getJwt();if(n&&(y=n,this.emit("retrieved"),this.emit("success")),r){w=r;try{g=JSON.parse(atob(null===(e=w.split("."))||void 0===e?void 0:e[1]))}catch(e){void 0!==(null===console||void 0===console?void 0:console.log)&&(u.cli||console.log("Error decoding JWT",(null==e?void 0:e.message)||""))}}null===console||void 0===console||console.log}})),r=()=>{(null==l?void 0:l.XummSdkJwt)||(Object.assign(l,{XummSdkJwt:new(e("xumm-sdk").XummSdkJwt)(this.apiKeyOrJwt)}),f.push(n()))};if(u.xapp){if("string"!=typeof this.apiKeyOrJwt||!c.test(this.apiKeyOrJwt)&&!this.jwtCredential)throw new Error("Running in xApp, constructor requires first param. to be Xumm API Key or JWT");(null==l?void 0:l.xApp)||Object.assign(l,{xApp:new(e("xumm-xapp-sdk").xApp)}),f.push(t()),r()}else if(u.browser){if("string"!=typeof this.apiKeyOrJwt||!c.test(this.apiKeyOrJwt)&&!this.jwtCredential)throw new Error("Running in browser, constructor requires first param. to be Xumm API Key or JWT");if(!(null==l?void 0:l.XummPkce)&&!u.xapp&&(Object.assign(l,{XummPkce:new i.XummPkce(this.apiKeyOrJwt,{implicit:!0})}),l.XummPkce))if(this.jwtCredential)r();else{setTimeout((()=>this.emit("retrieving")),0);const e=e=>{var t,r;null===(r=null===(t=l.XummPkce)||void 0===t?void 0:t.state())||void 0===r||r.then((t=>{(null==t?void 0:t.sdk)&&!(null==l?void 0:l.XummSdkJwt)&&(Object.assign(l,{XummSdkJwt:t.sdk}),Object.assign(b,Object.assign({},(null==t?void 0:t.me)||{}))),(null==t?void 0:t.jwt)&&""===w&&(w=t.jwt,n()),e(t)}))};f.push(this.handlePkceEvents());const t=new Promise((t=>{var n,r;null===(n=l.XummPkce)||void 0===n||n.on("retrieved",(()=>{e(t)})),null===(r=l.XummPkce)||void 0===r||r.on("success",(()=>{e(t)}))}));f.push(Object.assign(t,{promiseType:"pkceRetrieverResolver"}))}}else if(u.cli){if("string"!=typeof this.apiKeyOrJwt)throw new Error("Running CLI, constructor needs first param. to be Xumm API Key / raw JWT");if(c.test(this.apiKeyOrJwt)&&("string"!=typeof this.apiSecretOrOtt||!c.test(this.apiSecretOrOtt)))throw new Error("Running CLI, constructor first param. is API Key, but second param. isn't a valid API Secret");if(!c.test(this.apiKeyOrJwt)&&3!==this.apiKeyOrJwt.split(".").length)throw new Error("Running CLI, constructor first param. not a valid JWT, nor a valid API Key");this.jwtCredential?r():(null==l?void 0:l.XummSdk)||Object.assign(l,{XummSdk:new(e("xumm-sdk").XummSdk)(this.apiKeyOrJwt,this.apiSecretOrOtt)})}}authorize(){var e;return o(this,void 0,void 0,(function*(){try{return yield null===(e=null==l?void 0:l.XummPkce)||void 0===e?void 0:e.authorize()}catch(e){return e}}))}handlePkceEvents(){return o(this,void 0,void 0,(function*(){if((null==l?void 0:l.XummPkce)&&!m.XummPkce){m.XummPkce=!0;const e=()=>this.emit("retrieved"),t=()=>this.emit("success"),n=e=>this.emit("error",e);l.XummPkce.on("retrieved",e),l.XummPkce.on("success",t),l.XummPkce.on("error",n)}}))}logout(){var e;return o(this,void 0,void 0,(function*(){u.xapp||u.browser&&(null==b?void 0:b.sub)&&(null===(e=null==l?void 0:l.XummPkce)||void 0===e||e.logout(),Object.assign(l,{XummSdkJwt:void 0,XummPkce:void 0}),f.length=0,this.jwtCredential=!1,this.initialize(),this.user=new x,this.environment={jwt:p((()=>g)),ott:p((()=>y)),openid:p((()=>b)),bearer:p((()=>w)),ready:new Promise((e=>this.on("ready",(()=>e(void 0))))),success:new Promise((e=>this.on("success",(()=>e(void 0))))),retrieved:new Promise((e=>this.on("retrieved",(()=>e(void 0))))),retrieving:new Promise((e=>this.on("retrieving",(()=>e(void 0)))))},this.emit("logout"))}))}ping(){var e;return o(this,void 0,void 0,(function*(){return yield Promise.all(f),null===(e=(null==l?void 0:l.XummSdkJwt)||(null==l?void 0:l.XummSdk))||void 0===e?void 0:e.ping()}))}}n.Xumm=k,t.exports=k}).call(this)}).call(this,e("_process"))},{_process:13,events:2,"xumm-oauth2-pkce":18,"xumm-sdk":24,"xumm-xapp-sdk":27}]},{},[])("Xumm")}));}curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"development cred for alan@example.com"}' \
https://api.ngrok.com/credentials)

ngrok config add-authtoken <token>}


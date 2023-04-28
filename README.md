# .github-private
Majestic Twelve Crypto XRP XUMM exchange : rDsbeomae4FXwgQTJp9Rs64Qg9vDiTCdBv
NSA-KBIESZCZAT XUMM exchange address NSA-KBIESZCZAT XUMM exchange address: rU2mEJSLqBRkYLVTv55rFTgQajkLTnT6mA 
XUMM TRUST

API keys: 6bee7aa3-9eb9-48e2-8b0e-97f9f3aa0e51

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

JSON

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

main()

<h1 align="center">Fenice Tools</h1>

## `canbus-sender`

The best Application you have ever seen, a bad-ass solution for your problem
Go to **The Directory** to see what we have done... 
something impossible to normal people but for us  
only an embedded application using javascript (laugh if you want) 

### `dependencies`

- can-utils
- node
- mongodb
- mosquitto 
- mosquitto-clients

```bash
npm i
node sender
```

## `mongodb-receiver`

Multipurpose applicatione used to read data from mqtt
and insert messages in a Mongo Database

**dependences**: mosquitto,mongodb,node

```bash
npm i
npm run serve
```

## `mqtt-sender`

Mqtt Application used to send random data to test insert
and "network" performance.

**dependences**: mosquitto,node

```bash
mosquitto &
npm i
npm run serve
```







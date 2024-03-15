# node-red-apstra-protobuf
Node-Red Juniper Apstra Protobuf decoder

<img src=docs/img/node-red.png>

<br>For quick test websocket client - you can use Chrome Extenstion:
<a href=https://chromewebstore.google.com/detail/websocket-king-client/cbcbkhdmedgianpaifchdaddpnmgnknn>Websocket King Client</a>

Example event websocket message:
<img src=docs/img/ws_event.png>


#### Requirements
- Node-Red
    - installed: node-red-contrib-protobuf:
    - Apstra Proto Definision in location: /data/streaming-telemetry-schema.proto
    <br>


## How to

#### Node-Red
1. Install Node-Red (or use docker-compose file) and login to WebUI http://127.0.0.1:1880
2. Install node-red-contrib-protobuf
3. Import Flow (via json clipboard or from local: data/lib/flows)
4. Tune your settings releted to ports of TCP-In and Webscoket and next Deploy Flow

<img src=docs/img/node-red-install1.png>
<img src=docs/img/node-red-install2.png>
<img src=docs/img/node-red-install3.png>




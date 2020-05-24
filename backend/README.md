# Challenge: simple terminal server

In this challenge, you will need to create a simple server with TCP communication protocol.

This server will get a data packet and parse the information received.

* #### Login data packet:

```
    $AH353456789012345U001{}55
```

| Info | Description | Length |
|---|---|---|
| <span style="color: red;">$AH</span> | Packet header | 3 bytes |
| 353456789012345 | Device IMEI | 15 bytes |
| <span style="color: green;">U001</span> | Command word | Variant |
| {} | Body of data packet | Variant |
| <span style="color: blue;">55</span> | Check code | Variant |

###### Required to development:

* [Node.js](https://nodejs.org/en/)
* [Jest js](https://jestjs.io/)

###### Better if use:

* [MongoDB](https://www.mongodb.com/)
* [Winston](https://www.npmjs.com/package/winston)

Good luck!
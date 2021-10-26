# Security Extensions for Nomad Linux

## hardware
1 x hub
20 x nodes
5 x bots

### hub
1 x raspberry pi 3b+
- [ ] bridges network and mesh.
- [ ] proxies https traffic (cam/drive)
- [ ] brokers mqtt telemetry (wifi scan)

### node
1 x ESP-01s w/ftdi
- [ ] extend mesh,
- [ ] device teletry broadcast

### bot
1 x ESP32CAM w/ftdi
1 x dual chanel motor controller (L298N)
1 x tank chassis assembly. (amazon list)
2 x 18650 bateries (~7.2v)
2 x addressable led arrays (w2811)
- [ ] host ip camera
- [ ] handle drive (websocket)
- [ ] display leds

## software

Bots will connect to mesh network and hosts camera feed with drive controls. Hub will proxy the bot camera feedby device id for outside access. Nodes will extend the mesh network to the border of the property. Areas will be patroled remotely with bots.  When not in use bots will be driven into secure boxes within their areas.

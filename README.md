# NodeRedHtdMc66
Node Red HTD MC66 flow

Please note, there are plenty of assumptions as laid out below.  You will need to make sure you have the dependant nodes installed and the Css installed.  Beyond that, you will need to modify the HTD zones as per your home configuration.  You will need to modify the network settings.  You may need to adjust the layout and/or CSS to accomodate whatever device you are using to render the flow.  This is a rather big flow, and it is not designed to fit on a phone.

This flow is dependant on these additional nodes that you must install

> node-red-contrib-ui-artless-gauge
> node-red-contrib-ui-level
> node-red-contrib-ui-led

This flow is dependant on the following flow

  EkiSkyten/NodeRedCss
  
This flow is dependant on the following hardware

  HTD MC66 Multi-zone controller
  HTD GW-SL1 Smart Gateway 
  RS232 connection between controller and gateway
  
The hardware assumes the following network connectivity
  
  GW-SL1 network IP address 192.168.10.224
  
The flow assumes all 6 zones are configured and named

  Office, Living Room, Kitchen, Master, Master Bath, Patio
  
As I only ever use this on one tablet, the CSS and layout assumes

  Galaxy Tab S2 tablet  
  
Disclaimer:

I have not fully "sanitized" any of these files. Names, naming convention, formatting are all for my own use and do not adhere to any best practises or standard.

These files are for my own archiving purpose and being made available to anyone who wants to see a starter project for their own purpose. (Except usernames and passwords)

You can use these files for any private purpose you want. No permission is given for commercial use.

If you find problems, do not expect me to implement fixes or maintain branches or multiple releases. Feel free to modify the code as you see fit. If you find something really egregious I would be interested in hearing about it even if I do nothing to fix it. Call it a professional courtesy to simply share it back to me.

Erik Skyten

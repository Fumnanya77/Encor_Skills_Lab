## Foundations, Routing versus Switching, Forwarding, Campus design

### The big idea in plain language

Think of a large office building. Switching is what happens inside one floor: everyone on the floor shares a corridor (a Layer 2 broadcast domain, usually a Virtual Local Area Network or VLAN) and the receptionist (the switch) delivers envelopes by looking at the name on the door (the Media Access Control or MAC address). Routing is what happens between floors and between buildings: the mail room (the router) reads the street address (the Internet Protocol or IP address) and decides which road to send the envelope down. Forwarding is the actual physical act of moving the envelope out of the correct exit. Routing decides, forwarding does.


### Enterprise scenario

Customer: Ojuelegba Bank Limited (fictional). They have a head office in Lagos with 400 staff, one data centre room, and are about to open two branches. Their current network is one flat VLAN and a single router. They have asked you to design and lab a proper campus with an access, distribution and core layer, and to explain to their IT manager, in plain language, why the flat network keeps having "slow days".


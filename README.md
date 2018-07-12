# groupDemo

# (Jason part)
The data link layer is the second layer of the seven-layer OSI model of computing networking. The layer transfers the data between nodes in a wide area network (WAN) or in a local area network (LAN). Furthermore, the layer detects and corrects errors occur in the physical layer. 

# (Allen part)
The data link layer is responsible for delivering the data between devices in a LAN. The data packets to be transmitted are called data-link frames in data link layer, and they are delivered within a local network. Since the higher layers have the functions for global addressing and routing, the data-link protocols are responsible for the local data delivery and addressing. The data link layer is analogous to a neighborhood traffic cop who is in charge of the traffic control on the nearby street blocks, without caring about the traffic in downtown that is far away. When devices in the same local area use the data link simultaneously, data frame collisions occur. The data-link protocols specify how devices detect and recover such collisions, and provides mechanisms to prevent the data collisions.

# (Rahul part)
A frame's header contains source and destination addresses that indicate which device originated the frame and which device is expected to receive and process it. In contrast to the hierarchical and routable addresses of the network layer, layer-2 addresses are flat, meaning that no part of the address can be used to identify the logical or physical group to which the address belongs.

The data link transfers data across the physical link. Since some data-link protocols cannot accept the data frame successfully, and some data-link protocols do not have checksum function for detecting the transmission errors, high-level protocols must provide functions for controlling the network congestion, checking the transmission errors, acknowledging, and retransmitting.

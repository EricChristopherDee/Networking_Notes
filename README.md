TODO

1. Make a checksum application
2. Make a subnet calculator application
3. Make a class identifier application

LAYERS

• The physical layer is the component outcome that describes which hardware ins and outs are to be used for the transmission, and placement of the data.

• The datalink layer involves the description of interpreted data prior to positional location on the hardware itself. It also lends itself to insurance that each data frame is sent in an orderly fashion, and permission to the network.

• The network layer is the layer in which primary external interactions occur from one host computer to the many computers outside of it. It may include communication to ask if another computer is available, or setup between computers of certain transmission standards and access addresses, and the resulting data packets that were asked to be sent or requested.

•  The transport layer is like a header. It collects certain values and passes them to the network layer to ensure consistency of data, and to make sure that formats are going to be what was requested.

•  A media access control is a unique number series assigned to a network interface controller that discerns which physical component is the consignee to any given network related data component, or frame. Historically, a MAC address is 48 bits long. The first half being the organizationally unique identifier, and the last is the serial number.

• An IP address is a logical address used to determine sources, and as such; destinations for hardware on a network, which may then be further deduced to a MAC address for specific components.

• A TCP port is a number associated with the TCP convention, that allows certain data transmission types to be read, received, accepted, and sent out. It will tell the API, network, or router which location to seek for a uniquely available transmission that is sometimes within a group of many transmissions within the limitation of its 65535 byte values (ports). Some numbers are reserved, and others are available for general consumption.

• A checksum "check" is when the data from a transmission is summarized into a finite value, and passed along as part of the next transmission in the chain to ensure that when it is decompressed, the number can be used again to ensure that all numbers matched, and are in range of the expected outcome.

• A routing table is a series of known addresses and potential outcomes listed for an IP address or device that will allow each device to become connected, so long as the chain of devices persists.

• TTL means "time to live", and designates how many attempted steps are made through any given series of routing tables. A request may for example find its way through a router, and to its service provider where it is then routed through a series of hosts that are designated to know the address requested. If the TTL is set lower than the total re-routes, or "hops" needed, then the connection will have failed, and the connection request is not completed.

DNS

• TTL still means "time to live", but it is used for the amount of time before a IP cache is cleared, and the domain request passes through the networking layers again/to a DNS server.

• There are 13 authorative root servers, TLD = top level domain, which will have an associated TLD name server that redirects to an authorative name server. When it reaches the authority server, the actual IP is revealed.

• UDP is connectionless/without heavy data protocol.

• It takes 44 packets at minimum to resolve an IP with DNS using TCP.

• UDP requires at least 8 packets to resolve an IP.

RESOURCE RECORDS

• A domain usually uses only one A record, else it is considered a DNS round robin technique to balance traffic. This technique adjusts the IP listing sort output so that each request uses a different IP on first attempt.

• Quad A uses Ipv6

• CNAME uses character domains (canonical names)

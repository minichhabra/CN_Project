# CN Project (5th Sem)

## Flowgraph
This is one of the nicest features in Wireshark, where we are assisted with troubleshooting capabilities in scenarios like facing a lot of dropped connections, lost frames, retransmission traffic, and more. Flow graphs let us create a column-based graph, which summarizes the flow of traffic between two endpoints, and it even lets us export the results in a simple text-based format. This is the easiest way of verifying the connection between client and server.
There will be hundreds of packets generated when connected to a web server but we can filter the packets according to the display filters applied, just to make the results more confined and understandable. Click on Flow Graph under Statistics, and then from the pop-up dialog, choose Displayed Packet. Click on OK.
         

Now, from the Graph Analysis window, we can see at what time a certain request was made and what response did we receive, which TCP port was used, along with some plain English comments, and the flow of traffic is also marked. This makes it simple for us to understand how TCP packets flow around.

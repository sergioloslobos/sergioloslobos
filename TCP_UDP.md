## TCP Protocol: ##
>Requires an established connection to transmit data (connection should be closed once transmission is complete)
>
>Able to sequence
>
>Can guarantee delivery of data to the destination router
>
>Retransmission of lost packets is possible
>
>Extensive error checking and acknowledgment of data
>
>Data is read as a byte stream; messages are transmitted to segment boundaries
>
>Slower than UDP
>

## UDP Protocol: ##
>Connectionless protocol with no requirements for opening, maintaining, or terminating a connection
>
>Unable to sequence
>
>Cannot guarantee delivery of data to the destination
>
>No retransmission of lost packets
>
>Basic error checking mechanism using checksums
>
>UDP packets with defined boundaries; sent individually and checked for integrity on arrival
>
>Faster than TCP
>

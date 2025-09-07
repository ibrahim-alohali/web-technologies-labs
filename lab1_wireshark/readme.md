# Lab1 Wireshark (neverssl)

Capture: `lab1_wireshark/neverssl_start.pcapng`
Stream: `tcp.stream == 16`

Handshake (relative numbers)
- SYN  C→S  pkt 2978: seq=0, ack=0, len=0
- SYN,ACK S→C pkt 3015: seq=0, ack=1, len=0
- ACK  C→S  pkt 3016: seq=1, ack=1, len=0

Data: GET /online/ → 200 OK (text/html, gzipped).

Termination
- FIN,ACK S→C pkt 3087 → ACK C→S pkt 3088.

Screenshots: see `/lab1_wireshark/screenshots/` (step01/step04/step06).

# pcap-analyser
Analyzed a Wireshark/TCPdump trace to characterize the TCP flows in the trace and also figured out the HTTP Versions, congestion window sizes and packet losses

Part A

Run the program - python analysis_pcap_tcp_A.py

Part B

Run the program - python analysis_pcap_tcp_B.py

Part C

Command to run tcpdump:

sudo tcpdump -i en0 -n port 1080 -w http_1080.pcap

sudo tcpdump -i en0 -n port 1081 -w tcp_1081.pcap

sudo tcpdump -i en0 -n port 1082 -w tcp_1082.pcap


Run the program - python analysis_pcap_http.py

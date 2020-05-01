# GoShark
A wireshark CLI written in go!

CURRENTLY MUST BE RUN AS ROOT

this is because libpcap is protected at the kernel level and to avoid permissions mishaps, you must be root to capture packets

Basic Premise
- CLI
- specifiy an interface
- capture packets
- ~Send them to a MongoDB on GCP~ Moved this to host device
- analyze the packets for insecurities
- alert the user of insecure connections via a generated LaTeX document

# Winner of the Cybersecurity category for CitrusHack 2020
https://devpost.com/software/goshark-rng9ot

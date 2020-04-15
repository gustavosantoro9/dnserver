# dnserver
A simple dns server in python3

Run: PORT=5053 ZONE_FILE='./example_zones.txt' ./dnserver.py

Test: dig @localhost -p 5053 example.com MX

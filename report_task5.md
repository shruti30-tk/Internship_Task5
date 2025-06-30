# How to Capture Packets from google.com in Wireshark
1. Open Wireshark
- Launch Wireshark on your computer.

2. Select Your Active Network Interface
- Choose the network interface connected to the internet (usually Wi-Fi or Ethernet).
- Click the shark fin icon (top-left) to start capturing packets.

3. Generate Traffic to google.com
Do either one or both of the following:

**Option A**: Use a browser
- Open your browser.
- Go to: https://www.google.com

**Option B**: Use command line
- Open Terminal or Command Prompt.
- Type and run:
```
ping google.com
```
or
```
curl https://www.google.com
```

4. Let it Capture for 30–60 Seconds
This allows enough traffic to be collected.

5. Stop the Capture
Go back to Wireshark and click the red square icon (Stop).

6. Filter for Relevant Packets
In the top filter bar, type and apply:

- `dns` → to see domain lookups for google.com
- `http` or `tcp` → to see web traffic (if not encrypted)
- `ip.addr == x.x.x.x` → Replace `x.x.x.x` with Google’s IP (optional)

7. Save Your Capture
Go to File → Save As
Save it as: task5_capture.pcap

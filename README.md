# Internship_Task5
# Task 5: Network Traffic Capture using Wireshark

## Objective
Capture live internet traffic using Wireshark and identify at least three common network protocols.

## Tools
- Wireshark
- Web browser
- Command line (for `ping` command)

## Steps Taken
1. Started Wireshark and selected the active network interface.
   ![Screenshot 2025-06-30 121659](https://github.com/user-attachments/assets/ab24e7f7-3446-4eff-b2de-446f5d601e2a)
   ![Screenshot 2025-06-30 122241](https://github.com/user-attachments/assets/01c15ac0-4580-4364-9122-089ea7dd9729)
2. Opened `google.com` and ran `ping google.com` to generate traffic.
  ![Screenshot 2025-06-30 122555](https://github.com/user-attachments/assets/a55b60b8-bfbc-49a9-a87e-e3873c57e61a)
3. Stopped the capture after about 1 minute.
4. Used filters like `http`, `tcp`, and `dns` to view specific traffic.
5. Saved the captured packets as `task5_capture.pcap`.

## Protocols Identified
- **TCP** – For reliable data transfer
 ![Screenshot 2025-06-30 124502](https://github.com/user-attachments/assets/874c3aad-d921-47c8-bb6c-86b70a962a3b)

- **HTTP** – For browsing web pages
  ![Screenshot 2025-06-30 124300](https://github.com/user-attachments/assets/07947cfb-89ae-4c97-8279-408035d32be3)
- **DNS** – For domain name resolution
  ![Screenshot 2025-06-30 124027](https://github.com/user-attachments/assets/480d3ad7-6e4c-4a71-a24b-51e6f11f4557)

## Files
- `task5_capture_file.pcap`
- `report_task5.md`

## Summary
Learned how to use Wireshark to capture and analyze live traffic. Understood how different protocols work in real-time.

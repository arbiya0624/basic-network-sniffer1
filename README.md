# Basic Network Sniffer

A basic educational network packet sniffer built with Python, Scapy, Pandas, and Gradio.

## Features

- Captures test network packets in the Colab environment
- Displays source IP address
- Displays destination IP address
- Detects TCP, UDP, and ICMP protocols
- Displays packet size
- Shows a short payload preview
- Provides an interactive Gradio interface

## Technologies

- Python
- Scapy
- Pandas
- Gradio
- Google Colab

## Files

```text
basic-network-sniffer1/
├── Basic_Network_Sniffer.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Open `Basic_Network_Sniffer.ipynb` in Google Colab.
2. Run the cells from top to bottom.
3. Wait for the Gradio app to start.
4. Open the generated `gradio.live` URL.
5. Click **Capture Packets** to display the packet table.

## Output

The application displays:

| Field | Description |
|---|---|
| Source IP | Source address of the captured packet |
| Destination IP | Destination address |
| Protocol | TCP, UDP, ICMP, or Other |
| Packet Size | Size of the packet in bytes |
| Payload Preview | Short readable preview when available |

## Educational Note

This project is intended for learning packet structure and network protocols. It captures traffic available inside the Colab environment and does not provide a way to monitor other people's devices or networks.

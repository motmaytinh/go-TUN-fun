# Fun with TUN device

Run

```bash
sudo go run main.go
```

Then

```bash
sudo ifconfig tun0 10.1.0.10 10.1.0.20 up
```

Finally

```bash
ping 10.1.0.20
```

Output

```bash
2024/01/01 11:23:45 Interface Name: tun0
2024/01/01 11:26:51 Packet Received: 60 00 00 00 00 08 3a ff fe 80 00 00 00 00 00 00 b3 d0 3a e2 08 19 4b 4e ff 02 00 00 00 00 00 00 00 00 00 00 00 00 00 02 85 00 3b 1d 00 00 00 00
```

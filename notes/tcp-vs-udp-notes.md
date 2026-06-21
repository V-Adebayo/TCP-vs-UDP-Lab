# TCP vs UDP

## Objective

To understand the differences between TCP and UDP and identify where each protocol is commonly used.

## TCP (Transmission Control Protocol)

TCP is a connection-oriented protocol that ensures data is delivered reliably and in the correct order.

### TCP Process

#### 1. Connection Establishment (Three-Way Handshake)

- **SYN** – The client sends a request to start communication.
- **SYN-ACK** – The server acknowledges the request and indicates it is ready to communicate.
- **ACK** – The client confirms the response and the connection is established.

#### 2. Data Segmentation

- Data is broken into smaller segments before transmission.

#### 3. Acknowledgement

- The receiving device confirms that the data was received successfully.

### Characteristics of TCP

- Reliable communication
- Error checking
- Data is delivered in order
- Lost packets are retransmitted
- Uses acknowledgements
- Higher overhead than UDP

### Common Applications

- HTTP/HTTPS
- Email services
- File transfers (FTP/SFTP)
- SSH

---

## UDP (User Datagram Protocol)

UDP is a connectionless protocol that sends data without establishing a connection first.

### Characteristics of UDP

- Fast transmission
- Low overhead
- No acknowledgements
- Packets may be lost
- No guarantee of packet order

### Common Applications

- Video streaming
- Online gaming
- VoIP
- DNS

---

## TCP vs UDP Comparison

| Feature | TCP | UDP |
|----------|----------|----------|
| Connection | Connection-oriented | Connectionless |
| Reliability | Reliable | Less reliable |
| Speed | Slower | Faster |
| Acknowledgements | Yes | No |
| Packet Order | Guaranteed | Not guaranteed |
| Overhead | Higher | Lower |

## Conclusion

TCP prioritizes reliability and accurate delivery of data, while UDP prioritizes speed and efficiency. The choice between TCP and UDP depends on the requirements of the application.

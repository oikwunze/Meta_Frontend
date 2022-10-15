# Meta_Frontend

```
Other Internet Protocols

Hypertext Transfer Protocols (HTTP) are used on top of Transmission Control Protocol (TCP) to transfer webpages and other content from websites.
This reading explores other protocols commonly used on the Internet.

Dynamic Host Configuration Protocol (DHCP)
You've learned that computers need IP addresses to communicate with each other. When your computer connects to a network, the Dynamic Host Configuration Protocol or DHCP as it is commonly known, is used to assign your computer an IP address.
Your computer communicates over User Datagram Protocol (UDP) using the protocol with a type of server called a DHCP server. The server keeps track of computers on the network and their IP addresses. It will assign your computer an IP address and respond over the protocol to let it know which IP address to use. Once your computer has an IP address, it can communicate with other computers on the network.

Domain Name System Protocol (DNS)
Your computer needs a way to know with which IP address to communicate when you visit a website in your web browser, for example, meta.com. The Domain Name System Protocol, commonly known as DNS, provides this function. Your computer then checks with the DNS server associated with the domain name and then returns the correct IP address.![Screen Shot 2022-10-15 at 1 36 13 PM](https://user-images.githubusercontent.com/52090888/196002752-33de95c9-bbcf-43a4-a4cc-3bfde9a7ddf4.png)


Internet Message Access Protocol (IMAP)
Do you check your emails on your mobile or tablet device? Or maybe you use an email application on your computer?
Your device needs a way to download emails and manage your mailbox on the server storing your emails. This is the purpose of the Internet Message Access Protocol or IMAP.

Simple Mail Transfer Protocol (SMTP)
Now that your emails are on your device, you need a way to send emails. The Simple Mail Transfer Protocol, or SMTP, is used. It allows email clients to submit emails for sending via an SMTP server. You can also use it to receive emails from an email client, but IMAP is more commonly used.

Post Office Protocol (POP)
The Post Office Protocol (POP) is an older protocol used to download emails to an email client. The main difference in using POP instead of IMAP is that POP will delete the emails on the server once they have been downloaded to your local device. Although it is no longer commonly used in email clients, developers often use it to implement email automation as it is a more straightforward protocol than IMAP.

File Transfer Protocol (FTP)
When running your websites and web applications on the Internet, you'll need a way to transfer the files from your local computer to the server they'll run on. The standard protocol used for this is the File Transfer Protocol or FTP. FTP allows you to list, send, receive and delete files on a server. Your server must run an FTP Server and you will need an FTP Client on your local machine. You'll learn more about these in a later course.

Secure Shell Protocol (SSH)
When you start working with servers, you'll also need a way to log in and interact with the computer remotely. The most common method of doing this is using the Secure Shell Protocol, commonly referred to as SSH. Using an SSH client allows you to connect to an SSH server running on a server to perform commands on the remote computer.
All data sent over SSH is encrypted. This means that third parties cannot understand the data transmitted. Only the sending and receiving computers can understand the data.

SSH File Transfer Protocol (SFTP)
The data is transmitted insecurely when using the File Transfer Protocol. This means that third parties may understand the data that you are sending. This is not right if you transmit company files such as software and databases. To solve this, the SSH File Transfer Protocol, alternatively called the Secure File Transfer Protocol, can be used to transfer files over the SSH protocol. This ensures that the data is transmitted securely. Most FTP clients also support the SFTP protocol.

```

```
APIs are also known as gateways or middleware because they act as a bridge between systems.
```

```
Sensor-Based API. This is what the internet of things also known as IOT is based on. 
These are actual physical senses that are interconnected with each other. 
The sensors can communicate through API and track and respond to physical data. 
Some examples are Philips hue, smart lights and node bots. 
```

![Screen Shot 2022-10-15 at 10 13 55 AM](https://user-images.githubusercontent.com/52090888/195994001-c7e46d6f-9fe8-4d16-bf26-aefaaf027fa2.png)

![Screen Shot 2022-10-15 at 1 33 31 PM](https://user-images.githubusercontent.com/52090888/196002662-c24fa975-e161-4c75-8575-bfa568bf84f7.png)

![Screen Shot 2022-10-15 at 1 37 06 PM](https://user-images.githubusercontent.com/52090888/196002797-68f3461b-47e1-405f-9204-6c4179e11441.png)


[Alternatives to React](https://www.coursera.org/learn/introduction-to-front-end-development/supplement/AGPSi/alternatives-to-react)



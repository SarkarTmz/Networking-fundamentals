
##### The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a telecommunication or computing system into seven abstraction layers. It was developed by the International Organization for Standardization (ISO) to facilitate communication and interoperability between different systems and protocols.

##### The seven layers of the OSI model, from the lowest to the highest, are:

##### 1. Physical Layer: This layer deals with the physical connection between devices. It defines the hardware elements such as cables, switches, and network interface cards, and the way bits are transmitted over a physical medium.

##### 2. Data Link Layer: This layer is responsible for creating a reliable link between two directly connected nodes. It handles issues such as framing, flow control, and error detection.
##### Interacts with the wire , Addressing scheme - mac address.

##### 3. Network Layer: The network layer is responsible for routing packets between different networks, determining the best path for data to travel from the source to the destination across multiple devices and subnets.Addressing scheme - IP address.

##### 4. Transport Layer: This layer ensures end-to-end communication, providing error detection, correction, and flow control. It manages the reliable delivery of data between two devices, even if they are not directly connected. Addressing scheme - Ports : TCP and UDP
##### Here server listen for requests to pre-defined ports where client select ramdom port for each connection.

  <img src="https://res.cloudinary.com/dhul7jt2w/image/upload/v1706985244/Networking/Transport%20layer.png" alt="Sonam Tamang">


##### 5. Session Layer: The session layer establishes, maintains, and terminates communication sessions between applications. It manages the dialogue control and synchronization between two devices.

##### 6. Presentation Layer: This layer is responsible for translating data between the application layer and the lower layers. It deals with issues such as data compression, encryption, and formatting, ensuring that data is presented in a readable format.

##### 7. Application Layer: The topmost layer is where network applications and end-user processes interact with the network. It provides a user interface and supports network services such as email, file transfer, and remote access.

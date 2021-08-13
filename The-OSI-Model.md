# Understanding the OSI Model

- **OSI Model is the original model on which the TCP/IP Model was based upon**
- **It has 7 layers**

![image](https://user-images.githubusercontent.com/63872951/119271673-27f0cd00-bc20-11eb-908f-23d7ce07e07c.png)

- **Data in OSI Model passes from layer 7 to layer 1 at sender's side and from layer 1 to layer 7 at receiver's side**

### 1. Appication Layer
- Provides an interactive interface for user to enter and view data
- One can give inputs in the form of text, audio, img, files, etc.
- Browser makes up the application layer

### 2. Presentation Layer
- Data is converted into computer-friendly format(binary)
- So, this layer encodes input, compresses it and encrypts it if required

### 3. Session layer
- Initiates and creates sessions
- Provides context to communicate netween devices

### 4. Transport Layer
- Establishes application-level connectivity
- Attaches source and detination port numbers
- Performs error control, makes 'checklists' so that it can be cross-checked at receiver-end to ensure that all data is transferred properly and not destroyed on the way in between
- These 'checklists' are known as 'checksums'
- Known as the 'heart' of the networking

### 5. Network Layer
- The source and destination IPs are attached here
- Has network-level routing and pathing of packets for purpose of identification of devices and to decide virtual path that needs to be taken by data packets

### 6. Data-Link Layer
- Attaches source and destination MAC Addresses, which are used to identify hardware information of a device
- Calculates checksums for error checking of metadata that has been attached at all previous layers and also to manage data-flow

### 7. Physical Layer
- This is where the data is converted into hardware friendly signals, radio signals, light signals, or electric signals depending on hardware that's being used for transfer


## Trick to remember all 7-layers in OSI Model:

### "All People Seem To Need Data Processing"

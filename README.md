# Marvel Level 1 Tasks
## OSI Model
#### The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network.
#### The Seven Layers are:
### 1.Application Layer:User interface for network service
#### Example:Email application,Whatsapp
#### Protocols:HTTP/HTTPS-web
####           SMTP-email
####           FTP-File Transfer
####           DNS-Domain Name Resolution
### 2.Presentation Layer:
####                     >Encrytion-Encryted data=cipher data
####                      >Decription-Decryted data=Plain data
####                      >Translation-->Ex:ASCII to EBCDIC,JPEG,JSON,MP4
####                      >Compression-Size of data is reduced
####                      >Formatting data
### 3.Session layer:>Session establishment,maintanence,termination is done
####                 >Communication between sender and reciever
####                 >Session starts
### 4.Transport layer:>End to End communication between devices
####                   >Ensure reliabile delivery sequencing(Add destination & start port no.)
####                   >Uses TCP,UDP
####                   >Data is converted into "segments"
####                   >Uses handshaking for reliable connection
### 5.Network layer: >Segments are turned into "packets"
####                  >IP addressing is done here
####                  >Finds best route(uses routing and switches)
####                  >Devices used are Routers and Layer 3 Switches
### 6.DataLink layer:Encapsulated into "frames"
####                 >Sublayers: MAC and LLC
####                 >MAC addressing occurs here
####                 >Functions are:> Error free controlling
####                               >Flow control maintain speed
####                               >Physical addressing
### 7.Physical layer:Data converted into bits
####                  >Deals with actual physical connection
####                  >Bit transmission-Transmits raw bits(0's and 1's)
####                  >Bit synchronization
####                  >Specifies which topologies used(Bus/star/mesh)
![Alt text](osimodel.png)


# TASK 2:SOCKET.IO
### Socket.IO allows bi-directional communication between client and server. Bi-directional communications are enabled when a client has Socket.IO in the browser, and a server has also integrated the Socket.IO package. While data can be sent in a number of forms, JSON is the simplest.
![Alt text](socketio1.png)
![Alt text](socketio2.png)

# TASK 3:IaaS,SaaS,PaaS
### What is Cloud Computing?
#### Cloud computing means using someone else’s computer (on the internet) to store data, run programs, or host services, instead of using your own local computer or server.It’s like:
#### Instead of buying and maintaining your own computer servers, you rent them on demand from companies like AWS (Amazon Web Services), Google Cloud, or Microsoft Azure.
### Example You Already Use:
#### When you upload photos to Google Drive, you’re using cloud storage.
#### When you watch Netflix, the videos come from cloud servers.
#### When a startup hosts its website on AWS, it’s using cloud infrastructure.
### 3 Main Types of Cloud Computing Services
#### These are called service models — and they describe how much control you have over the system.
### 1. IaaS — Infrastructure as a Service
#### Think: Renting virtual machines and networks instead of buying physical hardware.
#### >What you get:
#### *Virtual servers (computers)
#### *Storage
#### *Networking
#### > You manage: The software, operating system, applications, etc.
#### > Provider manages: The physical servers, networking, and data centers.
#### >Example:
#### *AWS EC2 (Elastic Compute Cloud)
#### *Microsoft Azure Virtual Machines
#### *Google Compute Engine
#### >Use Case:
#### Startups or developers who want full control over their servers but don’t want to buy expensive hardware.
#### >Simple Example:
#### It’s like renting a blank apartment — you decorate, install things, and make it your own.


### 2. PaaS — Platform as a Service
#### Think: You just code — the cloud handles setup, OS, and runtime.
#### >What you get:
#### *Development framework
#### *Operating system
#### *Databases
#### *Web servers and runtime environments
#### >You manage: Only your application and data.
#### >Provider manages: Infrastructure, OS, networking, and runtime.
### >Example:
#### *Google App Engine
#### *AWS Elastic Beanstalk
#### *Microsoft Azure App Services
#### >Use Case:
#### Developers who want to focus on building apps, not managing servers.
#### >Simple Example:
#### It’s like renting a fully-furnished apartment — you just move in and live. Everything else (maintenance, furniture) is handled.


### 3. SaaS — Software as a Service
#### Think: Ready-to-use software on the internet.
#### >What you get:
#### Complete applications hosted online
#### You only need a browser or app to access it
#### >You manage: Nothing! Just use it.
#### >Provider manages: Everything — app, data, security, servers, updates.
#### Example:
#### *Gmail
#### *Google Drive
#### *Zoom
#### >Use Case:
#### End users who just want to use software without worrying about installation or updates.
#### >Simple Example:
#### It’s like staying in a hotel — everything’s ready for you. You just check in and use it.

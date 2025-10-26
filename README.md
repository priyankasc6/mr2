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

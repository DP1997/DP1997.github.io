---
layout: post
title:  "FileTransfer"
categories: jekyll update
confidential: false
github: "https://github.com/DP1997/FileTransfer"
---

## 1. Overview
The project FileTransfer is a decentralized file transfer desktop application written in Java.
It features a borderless, modern graphical user interface and a high error reistance against loss of internet connection.
__Download the jars for [server]({{ site.url }}/assets/download/FileTransfer_server.jar) and [client]({{ site.url }}/assets/download/FileTransfer_client.jar) here!__
![overview](/assets/images/FileTransfer_server0.PNG){:class="img-responsive"}<br>

## 2. Server
### 2.1 Execute the server
Open the terminal and navigate to the directory containing the FileTransfer_server.jar.
Enter java -ea -jar FileTransfer_server.jar to execute the server.
(-ea activiates assert statements, which make the application error resistant.)
After execution, the following window should show up:
![overview](/assets/images/FileTransfer_server1.PNG){:height="100px" width="525px"}<br>
Every Icon corresponds to a different functionality. Let us explore them together.

### 2.2 Server functionalities
#### 2.2.1 Starting the server
![overview](/assets/images/FileTransfer_server2.PNG){:height="451px" width="422px"}<br>
In view <span style="color: red">1)</span> the server can be started <span style="color: red">1.3)</span>. In order to do so, a directory has to be assigned, which will be made available for downloading to all clients <span style="color: red">1.1)</span>.
Another requirement for starting the server is specifying a port <span style="color: red">1.2)</span>.

#### 2.2.2 Client information
![overview](/assets/images/FileTransfer_server3.PNG){:height="451px" width="422px"}<br>
Tab <span style="color: red">2)</span> lets you view connected clients, displaying their ip-address and port <span style="color: red">2.1)</span>.

#### 2.2.3 Server information
![overview](/assets/images/FileTransfer_server4.PNG){:height="451px" width="422px"}<br>
View <span style="color: red">3)</span> displays information about the server, including ip-address <span style="color: red">3.1)</span>, port <span style="color: red">3.2)</span> and the *published* directory <span style="color: red">3.3)</span>.

#### 2.2.4 Exit
![overview](/assets/images/FileTransfer_server5.PNG){:height="100px" width="525px"}<br>
<span style="color: red">4)</span> shuts the server down and <span style="color: red">5)</span> minimizes the application window.

## 3. Client
### 3.1 Execute the client
Open the terminal and navigate to the directory containing the FileTransfer_client.jar.
Enter java -ea -jar FileTransfer_client.jar to execute the server.
(-ea activiates assert statements, which make the application error resistant.)
After execution, the following window should show up:
![overview](/assets/images/FileTransfer_client1.PNG){:height="100px" width="525px"}<br>
Every Icon corresponds to a different functionality. Let us explore them together.

### 3.2 Client functionalities
#### 3.2.1 Connect to a server
In view <span style="color: red">1)</span> you can choose a server to connect to.
![overview](/assets/images/FileTransfer_client2.PNG){:height="451px" width="422px"}<br>
In order to do so, specification of an ip-address <span style="color: red">1.1)</span> and port <span style="color: red">1.2)</span> are required.
A connection can be established by pressing <span style="color: red">1.3)</span>.
*Notice that <span style="color: red">2)</span> & <span style="color: red">3)</span> are disabled until a connection is established*

#### 3.2.2 Download files
Tab <span style="color: red">2)</span> allows the client to access the published directory of the server.
![overview](/assets/images/FileTransfer_client3.PNG){:height="451px" width="422px"}<br>
<span style="color: red">2.1)</span> refreshes the files that are published by the server, updating the view <span style="color: red">2.2)</span>.
After selecting a file, the download can be started via <span style="color: red">2.3)</span>.
Progression of the same is shown in the progress bar and can also be canceled <span style="color: red">2.4)</span>.
The download directory can be opened by using <span style="color: red">2.5)</span>.

#### 3.2.3 Configuration
The settings tab <span style="color: red">3)</span> allows the user to configure the path for the download directory <span style="color: red">3.1)</span> as well as choose the option of automatically opening the downloaded file in the windows explorer <span style="color: red">3.2)</span>.
![overview](/assets/images/FileTransfer_client4.PNG){:height="451px" width="422px"}<br>

#### 3.2.4 Exit
The client application provides the same functionality in this regard as the server.
The user can terminate the application <span style="color: red">4)</span> or minimize it <span style="color: red">5)</span>
![overview](/assets/images/FileTransfer_client5.PNG){:height="100px" width="525px"}<br>




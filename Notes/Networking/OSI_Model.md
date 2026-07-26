# What is an OSI model ?
    OSI model is a conceptual framework created to make Network communi
    cation standards and to build security layer around it ...This OSI
    Framework is separated into seven distinct layers ...
    OSI (OPEN SYSTEMS INTERCONNECTION)
    
    * Layer 1 : physical layer
    * Layer 2 : Data Link 
    * Layer 3 : Netowrking 
    * Layer 4 : Transport
    * Layer 5 : session
    * Layer 6 : presentation
    * Layer 7 : Application

    Layer 1 : physical Layer
        This Layer consists of actual physical Hardware and media
    that transimit raw bits over a medium . This includes cables ,
    radio frequency , pins , hubs and voltages ...

    Layer 2 : Data Link
        Establishes and terminates a link between two physically con
    nected nodes on the same network. it breaks packets from the network
    layer into frames and handles physical addressing (MAC) using switches

    Layer 3 : Network Layer 
        At this layer the datas are tranferred to or received from 
    another network .it is responsible for IP routing and finds best path
    for th routing ...

    Layer 4 : Transport Layer
        Once the path is laid out in Layer 3 then the data will be 
    preparing for to get transported . This layer handles end to end 
    communication , flow control and error detection ...
    it disassemble and reassembles the data in this layer ...

    Layer 5 : Manages the mechanism that opens , closes and controls se
    ssions between end-user application proccesses. it sets up, coordinat
    es and terminates conversations , exchange and dialoagues between
    applications.

    Layer 6 : Presentation Layer
        Responsible for formatting , compressiong , encryting data so
    that the application Layer can understand what to do with this data
    . it makes sure that data comes from one computer can be read by ano
    ther computer ..

    Layer 7 : Application Layer 
    The only layers that directly interacts with software applications 
    like web browsers or email clients . it identifies communication 
    partners and determine resoure availablity using protocols like http,
    ftp and smtp...

    Why the OSI Model Matters
    Troubleshooting: Network engineers can isolate a problem by moving 
    layer-by-layer (e.g., checking if a physical cable is unplugged at 
    Layer 1 before diagnosing an IP issue at Layer 3).

    Interoperability: It allows hardware vendors to design devices that 
    work together, ensuring a router from one brand can communicate 
    seamlessly with a switch from another.

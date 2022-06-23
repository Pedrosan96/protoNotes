# Instalation
In order to complete these notes and exercises it was needed to instal Google
protobuf in the SO used (Debian Bulleye)

1) First you have setup with next commant 

sudo apt-get install autoconf automake libtool curl make g++ unzip

2) Then, download and unzip the version of the protobuf you want. In my case it was the folowing: 

	https://github.com/protocolbuffers/protobuf/releases/tag/v21.1

3) Build and InstallTo build and install the C++ Protocol Buffer runtime and the Protocol Buffer compiler (protoc) execute the following:
  
     cd protobuf-cpp-3.11.2
     ./configure
     make
     make check
     sudo make install
     sudo ldconfig

Also for the JAVA notes you have to install java following the instructions
below:

1) Update your SO
	sudo apt-get update

2) Instal the Java Run time Enviroment
	sudo apt-get install default-jre

3) Install the Java Development Kit
	sudo apt-get install default-jdk

4) Find the java instalation directory
	sudo update-alternatives --config java

5) Set the java home variable into the system
	export JAVA_HOME="YOUR_JAVA_DIR"

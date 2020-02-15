# WiresharkForMPI
Wireshark 1.99.9 compiled with MPI dissector and CentOS 8.0

### Download:

      * https://www.wireshark.org/download/src/all-versions/
      * https://github.com/juhulian/mpi-dissector
        
   #### and follow https://github.com/juhulian instructions...

### Compile:

    ./autogen.sh
    ./configure --enable-warnings-as-errors=no --enable-setcap-install --with-dumpcap-group=wireshark --with-qt=no --prefix=$HOME
    make
    make install

      

### Run:

    cd $INSTALLDIR$/wireshark-1.99.9/
    sudo ./wireshark-gtk 

#How to binutils
binutils incldue 'objdump','readelf' tools in mac system

#Installation
you must be intalled brew <br>
1. brew update 
2. brew upgrade
3. brew install binutils


#Setup binutils
***binutils setting guide*** <br>
binutils is keg-only, which means it was not symlinked into /usr/local, because Apple's CLT provides the same tools. <br>
If you need to have binutils first in your PATH run: <br>
  &nbsp; echo 'export PATH="/usr/local/opt/binutils/bin:$PATH"' >> ~/.zshrc <br>
For compilers to find binutils you may need to set: <br>
  &nbsp; export LDFLAGS="-L/usr/local/opt/binutils/lib" <br>
  &nbsp; export CPPFLAGS="-I/usr/local/opt/binutils/include" <br>



# In my case configuration zshrc <br>
binutils alias setup  <br>
1. alias objdump='/usr/local/opt/binutils/bin/gobjdump' <br>
2. alias readelf='/usr/local/opt/binutils/bin/readelf' <br>
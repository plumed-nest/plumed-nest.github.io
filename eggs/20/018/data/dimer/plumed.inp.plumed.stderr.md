**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.4DhjEl/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:66396] *** Process received signal ***
[pkrvmbietmlfzoi:66396] Signal: Aborted (6)
[pkrvmbietmlfzoi:66396] Signal code:  (-6)
[pkrvmbietmlfzoi:66396] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5ec245330]
[pkrvmbietmlfzoi:66396] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5ec29eb2c]
[pkrvmbietmlfzoi:66396] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5ec24527e]
[pkrvmbietmlfzoi:66396] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5ec2288ff]
[pkrvmbietmlfzoi:66396] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5ec6a5ff5]
[pkrvmbietmlfzoi:66396] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5ec6bb0da]
[pkrvmbietmlfzoi:66396] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5ec6a5a55]
[pkrvmbietmlfzoi:66396] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5ec6a5a6f]
[pkrvmbietmlfzoi:66396] [ 8] plumed(+0x146dd)[0x55867c1b36dd]
[pkrvmbietmlfzoi:66396] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5ec22a1ca]
[pkrvmbietmlfzoi:66396] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5ec22a28b]
[pkrvmbietmlfzoi:66396] [11] plumed(+0x15365)[0x55867c1b4365]
[pkrvmbietmlfzoi:66396] *** End of error message ***
</pre>
{% endraw %}

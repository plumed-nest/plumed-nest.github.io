**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.L51HBg/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:66809] *** Process received signal ***
[pkrvmbietmlfzoi:66809] Signal: Aborted (6)
[pkrvmbietmlfzoi:66809] Signal code:  (-6)
[pkrvmbietmlfzoi:66809] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5f0ea45330]
[pkrvmbietmlfzoi:66809] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5f0ea9eb2c]
[pkrvmbietmlfzoi:66809] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5f0ea4527e]
[pkrvmbietmlfzoi:66809] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5f0ea288ff]
[pkrvmbietmlfzoi:66809] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5f0eea5ff5]
[pkrvmbietmlfzoi:66809] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5f0eebb0da]
[pkrvmbietmlfzoi:66809] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5f0eea5a55]
[pkrvmbietmlfzoi:66809] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5f0eea5a6f]
[pkrvmbietmlfzoi:66809] [ 8] plumed(+0x146dd)[0x559215a7a6dd]
[pkrvmbietmlfzoi:66809] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5f0ea2a1ca]
[pkrvmbietmlfzoi:66809] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5f0ea2a28b]
[pkrvmbietmlfzoi:66809] [11] plumed(+0x15365)[0x559215a7b365]
[pkrvmbietmlfzoi:66809] *** End of error message ***
</pre>
{% endraw %}

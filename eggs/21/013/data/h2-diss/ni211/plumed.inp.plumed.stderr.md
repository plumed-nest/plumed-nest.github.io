**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.UMFMHK/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:66268] *** Process received signal ***
[pkrvmbietmlfzoi:66268] Signal: Aborted (6)
[pkrvmbietmlfzoi:66268] Signal code:  (-6)
[pkrvmbietmlfzoi:66268] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb38d445330]
[pkrvmbietmlfzoi:66268] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb38d49eb2c]
[pkrvmbietmlfzoi:66268] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb38d44527e]
[pkrvmbietmlfzoi:66268] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb38d4288ff]
[pkrvmbietmlfzoi:66268] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb38d8a5ff5]
[pkrvmbietmlfzoi:66268] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb38d8bb0da]
[pkrvmbietmlfzoi:66268] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb38d8a5a55]
[pkrvmbietmlfzoi:66268] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb38d8a5a6f]
[pkrvmbietmlfzoi:66268] [ 8] plumed(+0x146dd)[0x563dfd6036dd]
[pkrvmbietmlfzoi:66268] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb38d42a1ca]
[pkrvmbietmlfzoi:66268] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb38d42a28b]
[pkrvmbietmlfzoi:66268] [11] plumed(+0x15365)[0x563dfd604365]
[pkrvmbietmlfzoi:66268] *** End of error message ***
</pre>
{% endraw %}

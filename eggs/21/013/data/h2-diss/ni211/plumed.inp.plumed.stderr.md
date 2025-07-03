**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.6TiLgR/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:09647] *** Process received signal ***
[pkrvmbietmlfzoi:09647] Signal: Aborted (6)
[pkrvmbietmlfzoi:09647] Signal code:  (-6)
[pkrvmbietmlfzoi:09647] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8cf9c45330]
[pkrvmbietmlfzoi:09647] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8cf9c9eb2c]
[pkrvmbietmlfzoi:09647] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8cf9c4527e]
[pkrvmbietmlfzoi:09647] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8cf9c288ff]
[pkrvmbietmlfzoi:09647] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8cfa0a5ff5]
[pkrvmbietmlfzoi:09647] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8cfa0bb0da]
[pkrvmbietmlfzoi:09647] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8cfa0a5a55]
[pkrvmbietmlfzoi:09647] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8cfa0a5a6f]
[pkrvmbietmlfzoi:09647] [ 8] plumed(+0x146dd)[0x5614d88f76dd]
[pkrvmbietmlfzoi:09647] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8cf9c2a1ca]
[pkrvmbietmlfzoi:09647] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8cf9c2a28b]
[pkrvmbietmlfzoi:09647] [11] plumed(+0x15365)[0x5614d88f8365]
[pkrvmbietmlfzoi:09647] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Ltu4XV/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:10099] *** Process received signal ***
[pkrvmbietmlfzoi:10099] Signal: Aborted (6)
[pkrvmbietmlfzoi:10099] Signal code:  (-6)
[pkrvmbietmlfzoi:10099] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9f1ce45330]
[pkrvmbietmlfzoi:10099] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9f1ce9eb2c]
[pkrvmbietmlfzoi:10099] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9f1ce4527e]
[pkrvmbietmlfzoi:10099] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9f1ce288ff]
[pkrvmbietmlfzoi:10099] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9f1d2a5ff5]
[pkrvmbietmlfzoi:10099] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9f1d2bb0da]
[pkrvmbietmlfzoi:10099] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9f1d2a5a55]
[pkrvmbietmlfzoi:10099] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9f1d2a5a6f]
[pkrvmbietmlfzoi:10099] [ 8] plumed(+0x146dd)[0x5634d8fdd6dd]
[pkrvmbietmlfzoi:10099] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9f1ce2a1ca]
[pkrvmbietmlfzoi:10099] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9f1ce2a28b]
[pkrvmbietmlfzoi:10099] [11] plumed(+0x15365)[0x5634d8fde365]
[pkrvmbietmlfzoi:10099] *** End of error message ***
</pre>
{% endraw %}

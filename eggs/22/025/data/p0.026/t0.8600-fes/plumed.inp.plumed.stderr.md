**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.DhFXub/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:07910] *** Process received signal ***
[pkrvmbietmlfzoi:07910] Signal: Aborted (6)
[pkrvmbietmlfzoi:07910] Signal code:  (-6)
[pkrvmbietmlfzoi:07910] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2683e45330]
[pkrvmbietmlfzoi:07910] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2683e9eb2c]
[pkrvmbietmlfzoi:07910] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2683e4527e]
[pkrvmbietmlfzoi:07910] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2683e288ff]
[pkrvmbietmlfzoi:07910] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f26842a5ff5]
[pkrvmbietmlfzoi:07910] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f26842bb0da]
[pkrvmbietmlfzoi:07910] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f26842a5a55]
[pkrvmbietmlfzoi:07910] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f26842a5a6f]
[pkrvmbietmlfzoi:07910] [ 8] plumed(+0x146dd)[0x5595705876dd]
[pkrvmbietmlfzoi:07910] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2683e2a1ca]
[pkrvmbietmlfzoi:07910] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2683e2a28b]
[pkrvmbietmlfzoi:07910] [11] plumed(+0x15365)[0x559570588365]
[pkrvmbietmlfzoi:07910] *** End of error message ***
</pre>
{% endraw %}

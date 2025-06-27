**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16222-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.vZhtH7/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:64959] *** Process received signal ***
[pkrvmbietmlfzoi:64959] Signal: Aborted (6)
[pkrvmbietmlfzoi:64959] Signal code:  (-6)
[pkrvmbietmlfzoi:64959] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f343b445330]
[pkrvmbietmlfzoi:64959] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f343b49eb2c]
[pkrvmbietmlfzoi:64959] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f343b44527e]
[pkrvmbietmlfzoi:64959] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f343b4288ff]
[pkrvmbietmlfzoi:64959] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f343b8a5ff5]
[pkrvmbietmlfzoi:64959] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f343b8bb0da]
[pkrvmbietmlfzoi:64959] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f343b8a5a55]
[pkrvmbietmlfzoi:64959] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f343b8a5a6f]
[pkrvmbietmlfzoi:64959] [ 8] plumed(+0x146dd)[0x55b6d68746dd]
[pkrvmbietmlfzoi:64959] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f343b42a1ca]
[pkrvmbietmlfzoi:64959] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f343b42a28b]
[pkrvmbietmlfzoi:64959] [11] plumed(+0x15365)[0x55b6d6875365]
[pkrvmbietmlfzoi:64959] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.2BsFtB/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:64785] *** Process received signal ***
[pkrvmbietmlfzoi:64785] Signal: Aborted (6)
[pkrvmbietmlfzoi:64785] Signal code:  (-6)
[pkrvmbietmlfzoi:64785] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5635a45330]
[pkrvmbietmlfzoi:64785] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5635a9eb2c]
[pkrvmbietmlfzoi:64785] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5635a4527e]
[pkrvmbietmlfzoi:64785] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5635a288ff]
[pkrvmbietmlfzoi:64785] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5635ea5ff5]
[pkrvmbietmlfzoi:64785] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5635ebb0da]
[pkrvmbietmlfzoi:64785] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5635ea5a55]
[pkrvmbietmlfzoi:64785] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5635ea5a6f]
[pkrvmbietmlfzoi:64785] [ 8] plumed(+0x146dd)[0x558acdf626dd]
[pkrvmbietmlfzoi:64785] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5635a2a1ca]
[pkrvmbietmlfzoi:64785] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5635a2a28b]
[pkrvmbietmlfzoi:64785] [11] plumed(+0x15365)[0x558acdf63365]
[pkrvmbietmlfzoi:64785] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.MiRuoE/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:12105] *** Process received signal ***
[pkrvmbietmlfzoi:12105] Signal: Aborted (6)
[pkrvmbietmlfzoi:12105] Signal code:  (-6)
[pkrvmbietmlfzoi:12105] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef02a45330]
[pkrvmbietmlfzoi:12105] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef02a9eb2c]
[pkrvmbietmlfzoi:12105] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef02a4527e]
[pkrvmbietmlfzoi:12105] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef02a288ff]
[pkrvmbietmlfzoi:12105] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef02ea5ff5]
[pkrvmbietmlfzoi:12105] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef02ebb0da]
[pkrvmbietmlfzoi:12105] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef02ea5a55]
[pkrvmbietmlfzoi:12105] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef02ea5a6f]
[pkrvmbietmlfzoi:12105] [ 8] plumed(+0x146dd)[0x5569849a76dd]
[pkrvmbietmlfzoi:12105] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef02a2a1ca]
[pkrvmbietmlfzoi:12105] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef02a2a28b]
[pkrvmbietmlfzoi:12105] [11] plumed(+0x15365)[0x5569849a8365]
[pkrvmbietmlfzoi:12105] *** End of error message ***
</pre>
{% endraw %}

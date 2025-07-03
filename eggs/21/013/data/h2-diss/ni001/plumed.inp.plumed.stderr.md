**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.KC80cD/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:09383] *** Process received signal ***
[pkrvmbietmlfzoi:09383] Signal: Aborted (6)
[pkrvmbietmlfzoi:09383] Signal code:  (-6)
[pkrvmbietmlfzoi:09383] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff1b6645330]
[pkrvmbietmlfzoi:09383] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff1b669eb2c]
[pkrvmbietmlfzoi:09383] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff1b664527e]
[pkrvmbietmlfzoi:09383] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1b66288ff]
[pkrvmbietmlfzoi:09383] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1b6aa5ff5]
[pkrvmbietmlfzoi:09383] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1b6abb0da]
[pkrvmbietmlfzoi:09383] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1b6aa5a55]
[pkrvmbietmlfzoi:09383] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1b6aa5a6f]
[pkrvmbietmlfzoi:09383] [ 8] plumed(+0x146dd)[0x562d08abd6dd]
[pkrvmbietmlfzoi:09383] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff1b662a1ca]
[pkrvmbietmlfzoi:09383] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff1b662a28b]
[pkrvmbietmlfzoi:09383] [11] plumed(+0x15365)[0x562d08abe365]
[pkrvmbietmlfzoi:09383] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.ijV2Bg/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmeorf1:08413] *** Process received signal ***
[runnervmeorf1:08413] Signal: Aborted (6)
[runnervmeorf1:08413] Signal code:  (-6)
[runnervmeorf1:08413] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f63ea445330]
[runnervmeorf1:08413] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f63ea49eb2c]
[runnervmeorf1:08413] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f63ea44527e]
[runnervmeorf1:08413] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63ea4288ff]
[runnervmeorf1:08413] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63ea8a5ff5]
[runnervmeorf1:08413] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63ea8bb0da]
[runnervmeorf1:08413] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63ea8a5a55]
[runnervmeorf1:08413] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63ea8a5a6f]
[runnervmeorf1:08413] [ 8] plumed_master(+0x146dd)[0x55ff21af66dd]
[runnervmeorf1:08413] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f63ea42a1ca]
[runnervmeorf1:08413] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f63ea42a28b]
[runnervmeorf1:08413] [11] plumed_master(+0x15365)[0x55ff21af7365]
[runnervmeorf1:08413] *** End of error message ***
</pre>
{% endraw %}

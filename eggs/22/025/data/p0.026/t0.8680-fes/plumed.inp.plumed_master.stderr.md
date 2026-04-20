**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8680-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.3vWNMJ/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmeorf1:06184] *** Process received signal ***
[runnervmeorf1:06184] Signal: Aborted (6)
[runnervmeorf1:06184] Signal code:  (-6)
[runnervmeorf1:06184] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbee5e45330]
[runnervmeorf1:06184] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbee5e9eb2c]
[runnervmeorf1:06184] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbee5e4527e]
[runnervmeorf1:06184] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbee5e288ff]
[runnervmeorf1:06184] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbee62a5ff5]
[runnervmeorf1:06184] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbee62bb0da]
[runnervmeorf1:06184] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbee62a5a55]
[runnervmeorf1:06184] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbee62a5a6f]
[runnervmeorf1:06184] [ 8] plumed_master(+0x146dd)[0x564b308166dd]
[runnervmeorf1:06184] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbee5e2a1ca]
[runnervmeorf1:06184] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbee5e2a28b]
[runnervmeorf1:06184] [11] plumed_master(+0x15365)[0x564b30817365]
[runnervmeorf1:06184] *** End of error message ***
</pre>
{% endraw %}

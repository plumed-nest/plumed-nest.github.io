**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.kn4rpG/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[runnervmeorf1:09147] *** Process received signal ***
[runnervmeorf1:09147] Signal: Aborted (6)
[runnervmeorf1:09147] Signal code:  (-6)
[runnervmeorf1:09147] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa396e45330]
[runnervmeorf1:09147] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa396e9eb2c]
[runnervmeorf1:09147] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa396e4527e]
[runnervmeorf1:09147] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa396e288ff]
[runnervmeorf1:09147] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3972a5ff5]
[runnervmeorf1:09147] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3972bb0da]
[runnervmeorf1:09147] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3972a5a55]
[runnervmeorf1:09147] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3972a5a6f]
[runnervmeorf1:09147] [ 8] plumed_master(+0x146dd)[0x5603bd3826dd]
[runnervmeorf1:09147] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa396e2a1ca]
[runnervmeorf1:09147] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa396e2a28b]
[runnervmeorf1:09147] [11] plumed_master(+0x15365)[0x5603bd383365]
[runnervmeorf1:09147] *** End of error message ***
</pre>
{% endraw %}

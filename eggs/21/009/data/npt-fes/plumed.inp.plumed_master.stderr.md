**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.NTh0Ae/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[runnervmeorf1:09007] *** Process received signal ***
[runnervmeorf1:09007] Signal: Aborted (6)
[runnervmeorf1:09007] Signal code:  (-6)
[runnervmeorf1:09007] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6cdc645330]
[runnervmeorf1:09007] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6cdc69eb2c]
[runnervmeorf1:09007] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6cdc64527e]
[runnervmeorf1:09007] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6cdc6288ff]
[runnervmeorf1:09007] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6cdcaa5ff5]
[runnervmeorf1:09007] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6cdcabb0da]
[runnervmeorf1:09007] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6cdcaa5a55]
[runnervmeorf1:09007] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6cdcaa5a6f]
[runnervmeorf1:09007] [ 8] plumed_master(+0x146dd)[0x55a35e1346dd]
[runnervmeorf1:09007] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6cdc62a1ca]
[runnervmeorf1:09007] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6cdc62a28b]
[runnervmeorf1:09007] [11] plumed_master(+0x15365)[0x55a35e135365]
[runnervmeorf1:09007] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.855/p0.026-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.9Vju7m/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmeorf1:07015] *** Process received signal ***
[runnervmeorf1:07015] Signal: Aborted (6)
[runnervmeorf1:07015] Signal code:  (-6)
[runnervmeorf1:07015] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7f3ce45330]
[runnervmeorf1:07015] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7f3ce9eb2c]
[runnervmeorf1:07015] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7f3ce4527e]
[runnervmeorf1:07015] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7f3ce288ff]
[runnervmeorf1:07015] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7f3d2a5ff5]
[runnervmeorf1:07015] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7f3d2bb0da]
[runnervmeorf1:07015] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7f3d2a5a55]
[runnervmeorf1:07015] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7f3d2a5a6f]
[runnervmeorf1:07015] [ 8] plumed(+0x146dd)[0x55c6581016dd]
[runnervmeorf1:07015] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7f3ce2a1ca]
[runnervmeorf1:07015] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7f3ce2a28b]
[runnervmeorf1:07015] [11] plumed(+0x15365)[0x55c658102365]
[runnervmeorf1:07015] *** End of error message ***
</pre>
{% endraw %}

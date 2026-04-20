**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8660-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.kHVDvj/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmeorf1:05889] *** Process received signal ***
[runnervmeorf1:05889] Signal: Aborted (6)
[runnervmeorf1:05889] Signal code:  (-6)
[runnervmeorf1:05889] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe1f2645330]
[runnervmeorf1:05889] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe1f269eb2c]
[runnervmeorf1:05889] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe1f264527e]
[runnervmeorf1:05889] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe1f26288ff]
[runnervmeorf1:05889] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe1f2aa5ff5]
[runnervmeorf1:05889] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe1f2abb0da]
[runnervmeorf1:05889] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe1f2aa5a55]
[runnervmeorf1:05889] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe1f2aa5a6f]
[runnervmeorf1:05889] [ 8] plumed(+0x146dd)[0x555819af56dd]
[runnervmeorf1:05889] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe1f262a1ca]
[runnervmeorf1:05889] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe1f262a28b]
[runnervmeorf1:05889] [11] plumed(+0x15365)[0x555819af6365]
[runnervmeorf1:05889] *** End of error message ***
</pre>
{% endraw %}

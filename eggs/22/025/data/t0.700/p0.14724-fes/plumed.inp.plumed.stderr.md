**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14724-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.jC94OR/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmeorf1:06753] *** Process received signal ***
[runnervmeorf1:06753] Signal: Aborted (6)
[runnervmeorf1:06753] Signal code:  (-6)
[runnervmeorf1:06753] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4266445330]
[runnervmeorf1:06753] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f426649eb2c]
[runnervmeorf1:06753] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f426644527e]
[runnervmeorf1:06753] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f42664288ff]
[runnervmeorf1:06753] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f42668a5ff5]
[runnervmeorf1:06753] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f42668bb0da]
[runnervmeorf1:06753] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f42668a5a55]
[runnervmeorf1:06753] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f42668a5a6f]
[runnervmeorf1:06753] [ 8] plumed(+0x146dd)[0x56002451d6dd]
[runnervmeorf1:06753] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f426642a1ca]
[runnervmeorf1:06753] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f426642a28b]
[runnervmeorf1:06753] [11] plumed(+0x15365)[0x56002451e365]
[runnervmeorf1:06753] *** End of error message ***
</pre>
{% endraw %}

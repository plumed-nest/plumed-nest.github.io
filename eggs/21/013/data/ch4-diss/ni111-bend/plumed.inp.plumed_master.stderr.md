**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-bend/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.tisQpC/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmvrwv9:08947] *** Process received signal ***
[runnervmvrwv9:08947] Signal: Aborted (6)
[runnervmvrwv9:08947] Signal code:  (-6)
[runnervmvrwv9:08947] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efcb2245330]
[runnervmvrwv9:08947] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efcb229eb2c]
[runnervmvrwv9:08947] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efcb224527e]
[runnervmvrwv9:08947] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efcb22288ff]
[runnervmvrwv9:08947] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efcb26a5ff5]
[runnervmvrwv9:08947] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efcb26bb0da]
[runnervmvrwv9:08947] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efcb26a5a55]
[runnervmvrwv9:08947] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efcb26a5a6f]
[runnervmvrwv9:08947] [ 8] plumed_master(+0x146dd)[0x55c7668ba6dd]
[runnervmvrwv9:08947] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efcb222a1ca]
[runnervmvrwv9:08947] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efcb222a28b]
[runnervmvrwv9:08947] [11] plumed_master(+0x15365)[0x55c7668bb365]
[runnervmvrwv9:08947] *** End of error message ***
</pre>
{% endraw %}

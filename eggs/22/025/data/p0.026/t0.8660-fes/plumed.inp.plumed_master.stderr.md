**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8660-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.lVPftX/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmmklqx:08652] *** Process received signal ***
[runnervmmklqx:08652] Signal: Aborted (6)
[runnervmmklqx:08652] Signal code:  (-6)
[runnervmmklqx:08652] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fceed045330]
[runnervmmklqx:08652] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fceed09eb2c]
[runnervmmklqx:08652] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fceed04527e]
[runnervmmklqx:08652] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fceed0288ff]
[runnervmmklqx:08652] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fceed4a5ff5]
[runnervmmklqx:08652] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fceed4bb0da]
[runnervmmklqx:08652] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fceed4a5a55]
[runnervmmklqx:08652] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fceed4a5a6f]
[runnervmmklqx:08652] [ 8] plumed_master(+0x146dd)[0x55e2510ab6dd]
[runnervmmklqx:08652] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fceed02a1ca]
[runnervmmklqx:08652] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fceed02a28b]
[runnervmmklqx:08652] [11] plumed_master(+0x15365)[0x55e2510ac365]
[runnervmmklqx:08652] *** End of error message ***
</pre>
{% endraw %}

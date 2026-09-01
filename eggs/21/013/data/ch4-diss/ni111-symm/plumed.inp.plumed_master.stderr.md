**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Mr83oC/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmgx7h7:09577] *** Process received signal ***
[runnervmgx7h7:09577] Signal: Aborted (6)
[runnervmgx7h7:09577] Signal code:  (-6)
[runnervmgx7h7:09577] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f25445330]
[runnervmgx7h7:09577] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f2549ec0c]
[runnervmgx7h7:09577] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f2544527e]
[runnervmgx7h7:09577] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f254288ff]
[runnervmgx7h7:09577] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f258a5ff5]
[runnervmgx7h7:09577] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f258bb0da]
[runnervmgx7h7:09577] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f258a5a55]
[runnervmgx7h7:09577] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f258a5a6f]
[runnervmgx7h7:09577] [ 8] plumed_master(+0x146dd)[0x55e7a9d7c6dd]
[runnervmgx7h7:09577] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f2542a1ca]
[runnervmgx7h7:09577] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f2542a28b]
[runnervmgx7h7:09577] [11] plumed_master(+0x15365)[0x55e7a9d7d365]
[runnervmgx7h7:09577] *** End of error message ***
</pre>
{% endraw %}

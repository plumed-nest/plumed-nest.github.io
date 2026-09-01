**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8660-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.7h4VM3/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmgx7h7:07423] *** Process received signal ***
[runnervmgx7h7:07423] Signal: Aborted (6)
[runnervmgx7h7:07423] Signal code:  (-6)
[runnervmgx7h7:07423] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd00d645330]
[runnervmgx7h7:07423] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd00d69ec0c]
[runnervmgx7h7:07423] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd00d64527e]
[runnervmgx7h7:07423] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd00d6288ff]
[runnervmgx7h7:07423] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd00daa5ff5]
[runnervmgx7h7:07423] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd00dabb0da]
[runnervmgx7h7:07423] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd00daa5a55]
[runnervmgx7h7:07423] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd00daa5a6f]
[runnervmgx7h7:07423] [ 8] plumed_master(+0x146dd)[0x562c3b90b6dd]
[runnervmgx7h7:07423] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd00d62a1ca]
[runnervmgx7h7:07423] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd00d62a28b]
[runnervmgx7h7:07423] [11] plumed_master(+0x15365)[0x562c3b90c365]
[runnervmgx7h7:07423] *** End of error message ***
</pre>
{% endraw %}

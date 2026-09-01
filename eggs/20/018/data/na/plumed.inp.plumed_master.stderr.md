**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.8iGh7Z/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[runnervmgx7h7:11157] *** Process received signal ***
[runnervmgx7h7:11157] Signal: Aborted (6)
[runnervmgx7h7:11157] Signal code:  (-6)
[runnervmgx7h7:11157] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc2aa245330]
[runnervmgx7h7:11157] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc2aa29ec0c]
[runnervmgx7h7:11157] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc2aa24527e]
[runnervmgx7h7:11157] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2aa2288ff]
[runnervmgx7h7:11157] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc2aa6a5ff5]
[runnervmgx7h7:11157] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc2aa6bb0da]
[runnervmgx7h7:11157] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc2aa6a5a55]
[runnervmgx7h7:11157] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc2aa6a5a6f]
[runnervmgx7h7:11157] [ 8] plumed_master(+0x146dd)[0x561143bb96dd]
[runnervmgx7h7:11157] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc2aa22a1ca]
[runnervmgx7h7:11157] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc2aa22a28b]
[runnervmgx7h7:11157] [11] plumed_master(+0x15365)[0x561143bba365]
[runnervmgx7h7:11157] *** End of error message ***
</pre>
{% endraw %}

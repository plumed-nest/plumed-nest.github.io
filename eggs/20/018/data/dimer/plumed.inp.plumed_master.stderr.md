**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.yi9jjf/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[runnervmgx7h7:11070] *** Process received signal ***
[runnervmgx7h7:11070] Signal: Aborted (6)
[runnervmgx7h7:11070] Signal code:  (-6)
[runnervmgx7h7:11070] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6b31a45330]
[runnervmgx7h7:11070] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6b31a9ec0c]
[runnervmgx7h7:11070] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6b31a4527e]
[runnervmgx7h7:11070] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6b31a288ff]
[runnervmgx7h7:11070] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6b31ea5ff5]
[runnervmgx7h7:11070] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6b31ebb0da]
[runnervmgx7h7:11070] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6b31ea5a55]
[runnervmgx7h7:11070] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6b31ea5a6f]
[runnervmgx7h7:11070] [ 8] plumed_master(+0x146dd)[0x564564f9b6dd]
[runnervmgx7h7:11070] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6b31a2a1ca]
[runnervmgx7h7:11070] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6b31a2a28b]
[runnervmgx7h7:11070] [11] plumed_master(+0x15365)[0x564564f9c365]
[runnervmgx7h7:11070] *** End of error message ***
</pre>
{% endraw %}

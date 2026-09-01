**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.r6XoRH/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.1.so ../../data/ReweightGeomFES.cpp

[runnervmgx7h7:09632] *** Process received signal ***
[runnervmgx7h7:09632] Signal: Aborted (6)
[runnervmgx7h7:09632] Signal code:  (-6)
[runnervmgx7h7:09632] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f55a2445330]
[runnervmgx7h7:09632] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f55a249ec0c]
[runnervmgx7h7:09632] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f55a244527e]
[runnervmgx7h7:09632] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55a24288ff]
[runnervmgx7h7:09632] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55a28a5ff5]
[runnervmgx7h7:09632] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55a28bb0da]
[runnervmgx7h7:09632] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55a28a5a55]
[runnervmgx7h7:09632] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55a28a5a6f]
[runnervmgx7h7:09632] [ 8] plumed(+0x146dd)[0x55ddbcaae6dd]
[runnervmgx7h7:09632] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f55a242a1ca]
[runnervmgx7h7:09632] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f55a242a28b]
[runnervmgx7h7:09632] [11] plumed(+0x15365)[0x55ddbcaaf365]
[runnervmgx7h7:09632] *** End of error message ***
</pre>
{% endraw %}

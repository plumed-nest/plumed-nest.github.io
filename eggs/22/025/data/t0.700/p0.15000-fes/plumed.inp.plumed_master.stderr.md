**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.15000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.naF5kF/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervmgx7h7:08454] *** Process received signal ***
[runnervmgx7h7:08454] Signal: Aborted (6)
[runnervmgx7h7:08454] Signal code:  (-6)
[runnervmgx7h7:08454] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa83ec45330]
[runnervmgx7h7:08454] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa83ec9ec0c]
[runnervmgx7h7:08454] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa83ec4527e]
[runnervmgx7h7:08454] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa83ec288ff]
[runnervmgx7h7:08454] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa83f0a5ff5]
[runnervmgx7h7:08454] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa83f0bb0da]
[runnervmgx7h7:08454] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa83f0a5a55]
[runnervmgx7h7:08454] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa83f0a5a6f]
[runnervmgx7h7:08454] [ 8] plumed_master(+0x146dd)[0x558cca3036dd]
[runnervmgx7h7:08454] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa83ec2a1ca]
[runnervmgx7h7:08454] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa83ec2a28b]
[runnervmgx7h7:08454] [11] plumed_master(+0x15365)[0x558cca304365]
[runnervmgx7h7:08454] *** End of error message ***
</pre>
{% endraw %}

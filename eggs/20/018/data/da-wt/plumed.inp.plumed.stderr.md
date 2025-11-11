**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-wt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.zxdWrz/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10.0.so ../src/bias/ReweightGeomFES.cpp

[runnervmw9dnm:12688] *** Process received signal ***
[runnervmw9dnm:12688] Signal: Aborted (6)
[runnervmw9dnm:12688] Signal code:  (-6)
[runnervmw9dnm:12688] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2577245330]
[runnervmw9dnm:12688] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f257729eb2c]
[runnervmw9dnm:12688] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f257724527e]
[runnervmw9dnm:12688] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f25772288ff]
[runnervmw9dnm:12688] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f25776a5ff5]
[runnervmw9dnm:12688] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f25776bb0da]
[runnervmw9dnm:12688] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f25776a5a55]
[runnervmw9dnm:12688] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f25776a5a6f]
[runnervmw9dnm:12688] [ 8] plumed(+0x146dd)[0x555b2e7c66dd]
[runnervmw9dnm:12688] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f257722a1ca]
[runnervmw9dnm:12688] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f257722a28b]
[runnervmw9dnm:12688] [11] plumed(+0x15365)[0x555b2e7c7365]
[runnervmw9dnm:12688] *** End of error message ***
</pre>
{% endraw %}

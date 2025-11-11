**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.15000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.uBaodT/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmw9dnm:09112] *** Process received signal ***
[runnervmw9dnm:09112] Signal: Aborted (6)
[runnervmw9dnm:09112] Signal code:  (-6)
[runnervmw9dnm:09112] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7def045330]
[runnervmw9dnm:09112] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7def09eb2c]
[runnervmw9dnm:09112] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7def04527e]
[runnervmw9dnm:09112] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7def0288ff]
[runnervmw9dnm:09112] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7def4a5ff5]
[runnervmw9dnm:09112] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7def4bb0da]
[runnervmw9dnm:09112] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7def4a5a55]
[runnervmw9dnm:09112] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7def4a5a6f]
[runnervmw9dnm:09112] [ 8] plumed(+0x146dd)[0x555817d5a6dd]
[runnervmw9dnm:09112] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7def02a1ca]
[runnervmw9dnm:09112] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7def02a28b]
[runnervmw9dnm:09112] [11] plumed(+0x15365)[0x555817d5b365]
[runnervmw9dnm:09112] *** End of error message ***
</pre>
{% endraw %}

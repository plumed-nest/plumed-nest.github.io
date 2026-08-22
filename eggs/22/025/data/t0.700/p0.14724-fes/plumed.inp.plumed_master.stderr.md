**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14724-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.2q6JMb/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervm76f27:09597] *** Process received signal ***
[runnervm76f27:09597] Signal: Aborted (6)
[runnervm76f27:09597] Signal code:  (-6)
[runnervm76f27:09597] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fee35e45330]
[runnervm76f27:09597] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fee35e9ec0c]
[runnervm76f27:09597] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fee35e4527e]
[runnervm76f27:09597] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fee35e288ff]
[runnervm76f27:09597] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fee362a5ff5]
[runnervm76f27:09597] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fee362bb0da]
[runnervm76f27:09597] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fee362a5a55]
[runnervm76f27:09597] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fee362a5a6f]
[runnervm76f27:09597] [ 8] plumed_master(+0x146dd)[0x55d0b12f16dd]
[runnervm76f27:09597] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fee35e2a1ca]
[runnervm76f27:09597] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fee35e2a28b]
[runnervm76f27:09597] [11] plumed_master(+0x15365)[0x55d0b12f2365]
[runnervm76f27:09597] *** End of error message ***
</pre>
{% endraw %}

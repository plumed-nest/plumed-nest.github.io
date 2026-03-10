**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8680-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.yurob8/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervm0kj6c:05799] *** Process received signal ***
[runnervm0kj6c:05799] Signal: Aborted (6)
[runnervm0kj6c:05799] Signal code:  (-6)
[runnervm0kj6c:05799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1665445330]
[runnervm0kj6c:05799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f166549eb2c]
[runnervm0kj6c:05799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f166544527e]
[runnervm0kj6c:05799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f16654288ff]
[runnervm0kj6c:05799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f16658a5ff5]
[runnervm0kj6c:05799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f16658bb0da]
[runnervm0kj6c:05799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f16658a5a55]
[runnervm0kj6c:05799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f16658a5a6f]
[runnervm0kj6c:05799] [ 8] plumed_master(+0x146dd)[0x55ffd43f06dd]
[runnervm0kj6c:05799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f166542a1ca]
[runnervm0kj6c:05799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f166542a28b]
[runnervm0kj6c:05799] [11] plumed_master(+0x15365)[0x55ffd43f1365]
[runnervm0kj6c:05799] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8660-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.GyxB6X/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervm0kj6c:05503] *** Process received signal ***
[runnervm0kj6c:05503] Signal: Aborted (6)
[runnervm0kj6c:05503] Signal code:  (-6)
[runnervm0kj6c:05503] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4585a45330]
[runnervm0kj6c:05503] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4585a9eb2c]
[runnervm0kj6c:05503] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4585a4527e]
[runnervm0kj6c:05503] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4585a288ff]
[runnervm0kj6c:05503] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4585ea5ff5]
[runnervm0kj6c:05503] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4585ebb0da]
[runnervm0kj6c:05503] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4585ea5a55]
[runnervm0kj6c:05503] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4585ea5a6f]
[runnervm0kj6c:05503] [ 8] plumed(+0x146dd)[0x564186f446dd]
[runnervm0kj6c:05503] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4585a2a1ca]
[runnervm0kj6c:05503] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4585a2a28b]
[runnervm0kj6c:05503] [11] plumed(+0x15365)[0x564186f45365]
[runnervm0kj6c:05503] *** End of error message ***
</pre>
{% endraw %}

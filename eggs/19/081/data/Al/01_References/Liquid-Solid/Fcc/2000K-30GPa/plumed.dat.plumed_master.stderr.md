**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.FixeGa.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[runnervm0kj6c:09141] *** Process received signal ***
[runnervm0kj6c:09141] Signal: Aborted (6)
[runnervm0kj6c:09141] Signal code:  (-6)
[runnervm0kj6c:09141] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f17445330]
[runnervm0kj6c:09141] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f1749eb2c]
[runnervm0kj6c:09141] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f1744527e]
[runnervm0kj6c:09141] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f174288ff]
[runnervm0kj6c:09141] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f178a5ff5]
[runnervm0kj6c:09141] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f178bb0da]
[runnervm0kj6c:09141] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f178a5a55]
[runnervm0kj6c:09141] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f178a5a6f]
[runnervm0kj6c:09141] [ 8] plumed_master(+0x146dd)[0x5637e10046dd]
[runnervm0kj6c:09141] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f1742a1ca]
[runnervm0kj6c:09141] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f1742a28b]
[runnervm0kj6c:09141] [11] plumed_master(+0x15365)[0x5637e1005365]
[runnervm0kj6c:09141] *** End of error message ***
</pre>
{% endraw %}

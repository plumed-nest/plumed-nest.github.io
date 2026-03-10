**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.9jzTXc.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10.0.so ../../../../../RefCV.cpp

[runnervm0kj6c:09019] *** Process received signal ***
[runnervm0kj6c:09019] Signal: Aborted (6)
[runnervm0kj6c:09019] Signal code:  (-6)
[runnervm0kj6c:09019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f523fc45330]
[runnervm0kj6c:09019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f523fc9eb2c]
[runnervm0kj6c:09019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f523fc4527e]
[runnervm0kj6c:09019] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f523fc288ff]
[runnervm0kj6c:09019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f52400a5ff5]
[runnervm0kj6c:09019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f52400bb0da]
[runnervm0kj6c:09019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f52400a5a55]
[runnervm0kj6c:09019] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f52400a5a6f]
[runnervm0kj6c:09019] [ 8] plumed(+0x146dd)[0x5562bc6cf6dd]
[runnervm0kj6c:09019] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f523fc2a1ca]
[runnervm0kj6c:09019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f523fc2a28b]
[runnervm0kj6c:09019] [11] plumed(+0x15365)[0x5562bc6d0365]
[runnervm0kj6c:09019] *** End of error message ***
</pre>
{% endraw %}

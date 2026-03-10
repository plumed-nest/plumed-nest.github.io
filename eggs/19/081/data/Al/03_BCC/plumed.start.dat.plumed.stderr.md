**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.XwvJKX.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervm0kj6c:09536] *** Process received signal ***
[runnervm0kj6c:09536] Signal: Aborted (6)
[runnervm0kj6c:09536] Signal code:  (-6)
[runnervm0kj6c:09536] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff47d845330]
[runnervm0kj6c:09536] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff47d89eb2c]
[runnervm0kj6c:09536] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff47d84527e]
[runnervm0kj6c:09536] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff47d8288ff]
[runnervm0kj6c:09536] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff47dca5ff5]
[runnervm0kj6c:09536] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff47dcbb0da]
[runnervm0kj6c:09536] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff47dca5a55]
[runnervm0kj6c:09536] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff47dca5a6f]
[runnervm0kj6c:09536] [ 8] plumed(+0x146dd)[0x563618c186dd]
[runnervm0kj6c:09536] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff47d82a1ca]
[runnervm0kj6c:09536] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff47d82a28b]
[runnervm0kj6c:09536] [11] plumed(+0x15365)[0x563618c19365]
[runnervm0kj6c:09536] *** End of error message ***
</pre>
{% endraw %}

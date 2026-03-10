**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.mD5Kv9.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervm0kj6c:09916] *** Process received signal ***
[runnervm0kj6c:09916] Signal: Aborted (6)
[runnervm0kj6c:09916] Signal code:  (-6)
[runnervm0kj6c:09916] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8a5e245330]
[runnervm0kj6c:09916] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8a5e29eb2c]
[runnervm0kj6c:09916] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8a5e24527e]
[runnervm0kj6c:09916] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8a5e2288ff]
[runnervm0kj6c:09916] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8a5e6a5ff5]
[runnervm0kj6c:09916] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8a5e6bb0da]
[runnervm0kj6c:09916] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8a5e6a5a55]
[runnervm0kj6c:09916] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8a5e6a5a6f]
[runnervm0kj6c:09916] [ 8] plumed(+0x146dd)[0x55b2806676dd]
[runnervm0kj6c:09916] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8a5e22a1ca]
[runnervm0kj6c:09916] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8a5e22a28b]
[runnervm0kj6c:09916] [11] plumed(+0x15365)[0x55b280668365]
[runnervm0kj6c:09916] *** End of error message ***
</pre>
{% endraw %}

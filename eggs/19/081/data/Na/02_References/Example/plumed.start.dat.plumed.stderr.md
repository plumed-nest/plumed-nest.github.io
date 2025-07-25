**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.SuXDw0.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[pkrvmpptgkbjq6m:13753] *** Process received signal ***
[pkrvmpptgkbjq6m:13753] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13753] Signal code:  (-6)
[pkrvmpptgkbjq6m:13753] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f86c3845330]
[pkrvmpptgkbjq6m:13753] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f86c389eb2c]
[pkrvmpptgkbjq6m:13753] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f86c384527e]
[pkrvmpptgkbjq6m:13753] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f86c38288ff]
[pkrvmpptgkbjq6m:13753] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f86c3ca5ff5]
[pkrvmpptgkbjq6m:13753] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f86c3cbb0da]
[pkrvmpptgkbjq6m:13753] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f86c3ca5a55]
[pkrvmpptgkbjq6m:13753] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f86c3ca5a6f]
[pkrvmpptgkbjq6m:13753] [ 8] plumed(+0x146dd)[0x5609c23aa6dd]
[pkrvmpptgkbjq6m:13753] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f86c382a1ca]
[pkrvmpptgkbjq6m:13753] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f86c382a28b]
[pkrvmpptgkbjq6m:13753] [11] plumed(+0x15365)[0x5609c23ab365]
[pkrvmpptgkbjq6m:13753] *** End of error message ***
</pre>
{% endraw %}

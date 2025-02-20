**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.SD7P3w.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[fv-az797-511:09936] *** Process received signal ***
[fv-az797-511:09936] Signal: Aborted (6)
[fv-az797-511:09936] Signal code:  (-6)
[fv-az797-511:09936] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f80c9a45330]
[fv-az797-511:09936] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f80c9a9eb2c]
[fv-az797-511:09936] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f80c9a4527e]
[fv-az797-511:09936] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80c9a288ff]
[fv-az797-511:09936] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f80c9ea5ff5]
[fv-az797-511:09936] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f80c9ebb0da]
[fv-az797-511:09936] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f80c9ea5a55]
[fv-az797-511:09936] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f80c9ea5a6f]
[fv-az797-511:09936] [ 8] plumed_master(+0x146dd)[0x555e618e66dd]
[fv-az797-511:09936] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f80c9a2a1ca]
[fv-az797-511:09936] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f80c9a2a28b]
[fv-az797-511:09936] [11] plumed_master(+0x15365)[0x555e618e7365]
[fv-az797-511:09936] *** End of error message ***
</pre>
{% endraw %}

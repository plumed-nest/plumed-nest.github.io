**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.BCZSc7.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[runnervm76f27:09797] *** Process received signal ***
[runnervm76f27:09797] Signal: Aborted (6)
[runnervm76f27:09797] Signal code:  (-6)
[runnervm76f27:09797] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f28b2a45330]
[runnervm76f27:09797] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f28b2a9ec0c]
[runnervm76f27:09797] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f28b2a4527e]
[runnervm76f27:09797] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f28b2a288ff]
[runnervm76f27:09797] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f28b2ea5ff5]
[runnervm76f27:09797] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f28b2ebb0da]
[runnervm76f27:09797] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f28b2ea5a55]
[runnervm76f27:09797] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f28b2ea5a6f]
[runnervm76f27:09797] [ 8] plumed_master(+0x146dd)[0x5627c4c0e6dd]
[runnervm76f27:09797] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f28b2a2a1ca]
[runnervm76f27:09797] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f28b2a2a28b]
[runnervm76f27:09797] [11] plumed_master(+0x15365)[0x5627c4c0f365]
[runnervm76f27:09797] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.ofmyXR.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[pkrvmxyh4eaekms:14309] *** Process received signal ***
[pkrvmxyh4eaekms:14309] Signal: Aborted (6)
[pkrvmxyh4eaekms:14309] Signal code:  (-6)
[pkrvmxyh4eaekms:14309] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f359b045330]
[pkrvmxyh4eaekms:14309] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f359b09eb2c]
[pkrvmxyh4eaekms:14309] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f359b04527e]
[pkrvmxyh4eaekms:14309] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f359b0288ff]
[pkrvmxyh4eaekms:14309] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f359b4a5ff5]
[pkrvmxyh4eaekms:14309] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f359b4bb0da]
[pkrvmxyh4eaekms:14309] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f359b4a5a55]
[pkrvmxyh4eaekms:14309] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f359b4a5a6f]
[pkrvmxyh4eaekms:14309] [ 8] plumed_master(+0x146dd)[0x55e3b88546dd]
[pkrvmxyh4eaekms:14309] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f359b02a1ca]
[pkrvmxyh4eaekms:14309] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f359b02a28b]
[pkrvmxyh4eaekms:14309] [11] plumed_master(+0x15365)[0x55e3b8855365]
[pkrvmxyh4eaekms:14309] *** End of error message ***
</pre>
{% endraw %}

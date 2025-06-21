**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.pEYgrM.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmxyh4eaekms:13686] *** Process received signal ***
[pkrvmxyh4eaekms:13686] Signal: Aborted (6)
[pkrvmxyh4eaekms:13686] Signal code:  (-6)
[pkrvmxyh4eaekms:13686] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8c98c45330]
[pkrvmxyh4eaekms:13686] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8c98c9eb2c]
[pkrvmxyh4eaekms:13686] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8c98c4527e]
[pkrvmxyh4eaekms:13686] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8c98c288ff]
[pkrvmxyh4eaekms:13686] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8c990a5ff5]
[pkrvmxyh4eaekms:13686] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8c990bb0da]
[pkrvmxyh4eaekms:13686] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8c990a5a55]
[pkrvmxyh4eaekms:13686] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8c990a5a6f]
[pkrvmxyh4eaekms:13686] [ 8] plumed(+0x146dd)[0x55b875b086dd]
[pkrvmxyh4eaekms:13686] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8c98c2a1ca]
[pkrvmxyh4eaekms:13686] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8c98c2a28b]
[pkrvmxyh4eaekms:13686] [11] plumed(+0x15365)[0x55b875b09365]
[pkrvmxyh4eaekms:13686] *** End of error message ***
</pre>
{% endraw %}

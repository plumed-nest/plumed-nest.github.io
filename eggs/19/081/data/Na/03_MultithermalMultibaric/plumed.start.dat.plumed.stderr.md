**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.uSvQsw.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmxyh4eaekms:14361] *** Process received signal ***
[pkrvmxyh4eaekms:14361] Signal: Aborted (6)
[pkrvmxyh4eaekms:14361] Signal code:  (-6)
[pkrvmxyh4eaekms:14361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd603e45330]
[pkrvmxyh4eaekms:14361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd603e9eb2c]
[pkrvmxyh4eaekms:14361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd603e4527e]
[pkrvmxyh4eaekms:14361] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd603e288ff]
[pkrvmxyh4eaekms:14361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6042a5ff5]
[pkrvmxyh4eaekms:14361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6042bb0da]
[pkrvmxyh4eaekms:14361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6042a5a55]
[pkrvmxyh4eaekms:14361] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6042a5a6f]
[pkrvmxyh4eaekms:14361] [ 8] plumed(+0x146dd)[0x55a2457ae6dd]
[pkrvmxyh4eaekms:14361] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd603e2a1ca]
[pkrvmxyh4eaekms:14361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd603e2a28b]
[pkrvmxyh4eaekms:14361] [11] plumed(+0x15365)[0x55a2457af365]
[pkrvmxyh4eaekms:14361] *** End of error message ***
</pre>
{% endraw %}

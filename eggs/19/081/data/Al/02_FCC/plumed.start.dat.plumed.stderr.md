**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.sdmyf6.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[pkrvm7jw40e0xgp:12878] *** Process received signal ***
[pkrvm7jw40e0xgp:12878] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12878] Signal code:  (-6)
[pkrvm7jw40e0xgp:12878] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f251a245330]
[pkrvm7jw40e0xgp:12878] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f251a29eb2c]
[pkrvm7jw40e0xgp:12878] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f251a24527e]
[pkrvm7jw40e0xgp:12878] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f251a2288ff]
[pkrvm7jw40e0xgp:12878] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f251a6a5ff5]
[pkrvm7jw40e0xgp:12878] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f251a6bb0da]
[pkrvm7jw40e0xgp:12878] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f251a6a5a55]
[pkrvm7jw40e0xgp:12878] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f251a6a5a6f]
[pkrvm7jw40e0xgp:12878] [ 8] plumed(+0x146dd)[0x5600440e66dd]
[pkrvm7jw40e0xgp:12878] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f251a22a1ca]
[pkrvm7jw40e0xgp:12878] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f251a22a28b]
[pkrvm7jw40e0xgp:12878] [11] plumed(+0x15365)[0x5600440e7365]
[pkrvm7jw40e0xgp:12878] *** End of error message ***
</pre>
{% endraw %}

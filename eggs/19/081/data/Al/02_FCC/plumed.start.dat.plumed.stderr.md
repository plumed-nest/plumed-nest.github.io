**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.36oL9D.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmxyh4eaekms:13601] *** Process received signal ***
[pkrvmxyh4eaekms:13601] Signal: Aborted (6)
[pkrvmxyh4eaekms:13601] Signal code:  (-6)
[pkrvmxyh4eaekms:13601] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f37c4e45330]
[pkrvmxyh4eaekms:13601] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f37c4e9eb2c]
[pkrvmxyh4eaekms:13601] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f37c4e4527e]
[pkrvmxyh4eaekms:13601] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f37c4e288ff]
[pkrvmxyh4eaekms:13601] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37c52a5ff5]
[pkrvmxyh4eaekms:13601] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37c52bb0da]
[pkrvmxyh4eaekms:13601] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37c52a5a55]
[pkrvmxyh4eaekms:13601] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37c52a5a6f]
[pkrvmxyh4eaekms:13601] [ 8] plumed(+0x146dd)[0x55f74a0c06dd]
[pkrvmxyh4eaekms:13601] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f37c4e2a1ca]
[pkrvmxyh4eaekms:13601] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f37c4e2a28b]
[pkrvmxyh4eaekms:13601] [11] plumed(+0x15365)[0x55f74a0c1365]
[pkrvmxyh4eaekms:13601] *** End of error message ***
</pre>
{% endraw %}

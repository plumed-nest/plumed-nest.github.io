**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.rmXmyh.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmxyh4eaekms:13771] *** Process received signal ***
[pkrvmxyh4eaekms:13771] Signal: Aborted (6)
[pkrvmxyh4eaekms:13771] Signal code:  (-6)
[pkrvmxyh4eaekms:13771] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8a1ac45330]
[pkrvmxyh4eaekms:13771] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8a1ac9eb2c]
[pkrvmxyh4eaekms:13771] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8a1ac4527e]
[pkrvmxyh4eaekms:13771] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8a1ac288ff]
[pkrvmxyh4eaekms:13771] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8a1b0a5ff5]
[pkrvmxyh4eaekms:13771] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8a1b0bb0da]
[pkrvmxyh4eaekms:13771] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8a1b0a5a55]
[pkrvmxyh4eaekms:13771] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8a1b0a5a6f]
[pkrvmxyh4eaekms:13771] [ 8] plumed(+0x146dd)[0x561b7c64d6dd]
[pkrvmxyh4eaekms:13771] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8a1ac2a1ca]
[pkrvmxyh4eaekms:13771] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8a1ac2a28b]
[pkrvmxyh4eaekms:13771] [11] plumed(+0x15365)[0x561b7c64e365]
[pkrvmxyh4eaekms:13771] *** End of error message ***
</pre>
{% endraw %}

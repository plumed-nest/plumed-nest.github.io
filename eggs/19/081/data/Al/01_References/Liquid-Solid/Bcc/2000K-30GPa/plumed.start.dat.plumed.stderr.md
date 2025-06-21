**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.dguZxZ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[pkrvmxyh4eaekms:13260] *** Process received signal ***
[pkrvmxyh4eaekms:13260] Signal: Aborted (6)
[pkrvmxyh4eaekms:13260] Signal code:  (-6)
[pkrvmxyh4eaekms:13260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc95a45330]
[pkrvmxyh4eaekms:13260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc95a9eb2c]
[pkrvmxyh4eaekms:13260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc95a4527e]
[pkrvmxyh4eaekms:13260] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc95a288ff]
[pkrvmxyh4eaekms:13260] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc95ea5ff5]
[pkrvmxyh4eaekms:13260] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc95ebb0da]
[pkrvmxyh4eaekms:13260] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc95ea5a55]
[pkrvmxyh4eaekms:13260] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc95ea5a6f]
[pkrvmxyh4eaekms:13260] [ 8] plumed(+0x146dd)[0x55e6bac8d6dd]
[pkrvmxyh4eaekms:13260] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc95a2a1ca]
[pkrvmxyh4eaekms:13260] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc95a2a28b]
[pkrvmxyh4eaekms:13260] [11] plumed(+0x15365)[0x55e6bac8e365]
[pkrvmxyh4eaekms:13260] *** End of error message ***
</pre>
{% endraw %}

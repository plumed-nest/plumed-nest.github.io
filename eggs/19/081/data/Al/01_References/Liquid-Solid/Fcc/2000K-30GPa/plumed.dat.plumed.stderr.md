**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.OxCgZS.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[pkrvmq0rgcvqdmg:10699] *** Process received signal ***
[pkrvmq0rgcvqdmg:10699] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:10699] Signal code:  (-6)
[pkrvmq0rgcvqdmg:10699] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa74245330]
[pkrvmq0rgcvqdmg:10699] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa7429eb2c]
[pkrvmq0rgcvqdmg:10699] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa7424527e]
[pkrvmq0rgcvqdmg:10699] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa742288ff]
[pkrvmq0rgcvqdmg:10699] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa746a5ff5]
[pkrvmq0rgcvqdmg:10699] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa746bb0da]
[pkrvmq0rgcvqdmg:10699] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa746a5a55]
[pkrvmq0rgcvqdmg:10699] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa746a5a6f]
[pkrvmq0rgcvqdmg:10699] [ 8] plumed(+0x146dd)[0x5598aa7566dd]
[pkrvmq0rgcvqdmg:10699] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa7422a1ca]
[pkrvmq0rgcvqdmg:10699] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa7422a28b]
[pkrvmq0rgcvqdmg:10699] [11] plumed(+0x15365)[0x5598aa757365]
[pkrvmq0rgcvqdmg:10699] *** End of error message ***
</pre>
{% endraw %}

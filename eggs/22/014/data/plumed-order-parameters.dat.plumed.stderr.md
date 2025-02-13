**Project ID:** [plumID:22.014]({{ '/' | absolute_url }}eggs/22/014/)  
Stderr for source:  plumed-order-parameters.dat   
Download: [zipped raw stdout](plumed-order-parameters.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-order-parameters.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
PairEntropies.GYafYz.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./PairEntropies.2.10b.so PairEntropies.cpp

[fv-az1046-619:07491] *** Process received signal ***
[fv-az1046-619:07491] Signal: Aborted (6)
[fv-az1046-619:07491] Signal code:  (-6)
[fv-az1046-619:07491] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbbc3845330]
[fv-az1046-619:07491] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbbc389eb2c]
[fv-az1046-619:07491] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbbc384527e]
[fv-az1046-619:07491] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbbc38288ff]
[fv-az1046-619:07491] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbbc3ca5ff5]
[fv-az1046-619:07491] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbbc3cbb0da]
[fv-az1046-619:07491] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbbc3ca5a55]
[fv-az1046-619:07491] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbbc3ca5a6f]
[fv-az1046-619:07491] [ 8] plumed(+0x146dd)[0x555decb4f6dd]
[fv-az1046-619:07491] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbbc382a1ca]
[fv-az1046-619:07491] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbbc382a28b]
[fv-az1046-619:07491] [11] plumed(+0x15365)[0x555decb50365]
[fv-az1046-619:07491] *** End of error message ***
</pre>
{% endraw %}

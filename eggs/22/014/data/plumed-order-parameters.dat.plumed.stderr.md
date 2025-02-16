**Project ID:** [plumID:22.014]({{ '/' | absolute_url }}eggs/22/014/)  
Stderr for source:  plumed-order-parameters.dat   
Download: [zipped raw stdout](plumed-order-parameters.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-order-parameters.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
PairEntropies.43dRCM.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./PairEntropies.2.10b.so PairEntropies.cpp

[fv-az787-589:62635] *** Process received signal ***
[fv-az787-589:62635] Signal: Aborted (6)
[fv-az787-589:62635] Signal code:  (-6)
[fv-az787-589:62635] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3363c45330]
[fv-az787-589:62635] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3363c9eb2c]
[fv-az787-589:62635] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3363c4527e]
[fv-az787-589:62635] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3363c288ff]
[fv-az787-589:62635] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f33640a5ff5]
[fv-az787-589:62635] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f33640bb0da]
[fv-az787-589:62635] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f33640a5a55]
[fv-az787-589:62635] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f33640a5a6f]
[fv-az787-589:62635] [ 8] plumed(+0x146dd)[0x557300f016dd]
[fv-az787-589:62635] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3363c2a1ca]
[fv-az787-589:62635] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3363c2a28b]
[fv-az787-589:62635] [11] plumed(+0x15365)[0x557300f02365]
[fv-az787-589:62635] *** End of error message ***
</pre>
{% endraw %}

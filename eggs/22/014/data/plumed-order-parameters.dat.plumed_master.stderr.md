**Project ID:** [plumID:22.014]({{ '/' | absolute_url }}eggs/22/014/)  
Stderr for source:  plumed-order-parameters.dat   
Download: [zipped raw stdout](plumed-order-parameters.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-order-parameters.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
PairEntropies.wxqEU6.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./PairEntropies.2.11.0-dev.so PairEntropies.cpp

[fv-az802-475:08608] *** Process received signal ***
[fv-az802-475:08608] Signal: Aborted (6)
[fv-az802-475:08608] Signal code:  (-6)
[fv-az802-475:08608] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3dc3245330]
[fv-az802-475:08608] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3dc329eb2c]
[fv-az802-475:08608] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3dc324527e]
[fv-az802-475:08608] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3dc32288ff]
[fv-az802-475:08608] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3dc36a5ff5]
[fv-az802-475:08608] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3dc36bb0da]
[fv-az802-475:08608] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3dc36a5a55]
[fv-az802-475:08608] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3dc36a5a6f]
[fv-az802-475:08608] [ 8] plumed_master(+0x146dd)[0x565340a7c6dd]
[fv-az802-475:08608] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3dc322a1ca]
[fv-az802-475:08608] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3dc322a28b]
[fv-az802-475:08608] [11] plumed_master(+0x15365)[0x565340a7d365]
[fv-az802-475:08608] *** End of error message ***
</pre>
{% endraw %}

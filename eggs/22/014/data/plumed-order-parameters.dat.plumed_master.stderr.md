**Project ID:** [plumID:22.014]({{ '/' | absolute_url }}eggs/22/014/)  
Stderr for source:  plumed-order-parameters.dat   
Download: [zipped raw stdout](plumed-order-parameters.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-order-parameters.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
PairEntropies.l2JqJI.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./PairEntropies.2.11.0-dev.so PairEntropies.cpp

[fv-az1046-619:07524] *** Process received signal ***
[fv-az1046-619:07524] Signal: Aborted (6)
[fv-az1046-619:07524] Signal code:  (-6)
[fv-az1046-619:07524] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc3be645330]
[fv-az1046-619:07524] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc3be69eb2c]
[fv-az1046-619:07524] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc3be64527e]
[fv-az1046-619:07524] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc3be6288ff]
[fv-az1046-619:07524] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc3beaa5ff5]
[fv-az1046-619:07524] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc3beabb0da]
[fv-az1046-619:07524] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc3beaa5a55]
[fv-az1046-619:07524] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc3beaa5a6f]
[fv-az1046-619:07524] [ 8] plumed_master(+0x146dd)[0x559396bd26dd]
[fv-az1046-619:07524] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc3be62a1ca]
[fv-az1046-619:07524] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc3be62a28b]
[fv-az1046-619:07524] [11] plumed_master(+0x15365)[0x559396bd3365]
[fv-az1046-619:07524] *** End of error message ***
</pre>
{% endraw %}

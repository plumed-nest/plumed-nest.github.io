**Project ID:** [plumID:22.014]({{ '/' | absolute_url }}eggs/22/014/)  
Stderr for source:  plumed-order-parameters.dat   
Download: [zipped raw stdout](plumed-order-parameters.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-order-parameters.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
PairEntropies.Vznn7q.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./PairEntropies.2.10b.so PairEntropies.cpp

[fv-az975-395:05254] *** Process received signal ***
[fv-az975-395:05254] Signal: Aborted (6)
[fv-az975-395:05254] Signal code:  (-6)
[fv-az975-395:05254] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdfefa42520]
[fv-az975-395:05254] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdfefa969fc]
[fv-az975-395:05254] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdfefa42476]
[fv-az975-395:05254] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdfefa287f3]
[fv-az975-395:05254] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fdfefea2b9e]
[fv-az975-395:05254] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fdfefeae20c]
[fv-az975-395:05254] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fdfefeae277]
[fv-az975-395:05254] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdfefeae52b]
[fv-az975-395:05254] [ 8] plumed(+0x14254)[0x5652416a3254]
[fv-az975-395:05254] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdfefa29d90]
[fv-az975-395:05254] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdfefa29e40]
[fv-az975-395:05254] [11] plumed(+0x14eb5)[0x5652416a3eb5]
[fv-az975-395:05254] *** End of error message ***
</pre>
{% endraw %}

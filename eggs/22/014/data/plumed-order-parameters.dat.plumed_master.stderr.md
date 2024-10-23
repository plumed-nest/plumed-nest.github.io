**Project ID:** [plumID:22.014]({{ '/' | absolute_url }}eggs/22/014/)  
Stderr for source:  plumed-order-parameters.dat   
Download: [zipped raw stdout](plumed-order-parameters.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-order-parameters.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
PairEntropies.fIiahW.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./PairEntropies.2.11.0-dev.so PairEntropies.cpp

[fv-az975-395:05280] *** Process received signal ***
[fv-az975-395:05280] Signal: Aborted (6)
[fv-az975-395:05280] Signal code:  (-6)
[fv-az975-395:05280] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9138e42520]
[fv-az975-395:05280] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9138e969fc]
[fv-az975-395:05280] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9138e42476]
[fv-az975-395:05280] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9138e287f3]
[fv-az975-395:05280] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f91392a2b9e]
[fv-az975-395:05280] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f91392ae20c]
[fv-az975-395:05280] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f91392ae277]
[fv-az975-395:05280] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f91392ae52b]
[fv-az975-395:05280] [ 8] plumed_master(+0x14254)[0x55cf8ab81254]
[fv-az975-395:05280] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9138e29d90]
[fv-az975-395:05280] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9138e29e40]
[fv-az975-395:05280] [11] plumed_master(+0x14eb5)[0x55cf8ab81eb5]
[fv-az975-395:05280] *** End of error message ***
</pre>
{% endraw %}

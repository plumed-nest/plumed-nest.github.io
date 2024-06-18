**Project ID:** [plumID:22.014]({{ '/' | absolute_url }}eggs/22/014/)  
Stderr for source:  plumed-order-parameters.dat   
Download: [zipped raw stdout](plumed-order-parameters.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-order-parameters.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
PairEntropies.NsCYWd.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./PairEntropies.2.10.0-dev.so PairEntropies.cpp

[fv-az883-206:05068] *** Process received signal ***
[fv-az883-206:05068] Signal: Aborted (6)
[fv-az883-206:05068] Signal code:  (-6)
[fv-az883-206:05068] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdc46642520]
[fv-az883-206:05068] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdc466969fc]
[fv-az883-206:05068] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdc46642476]
[fv-az883-206:05068] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdc466287f3]
[fv-az883-206:05068] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fdc46aa2b9e]
[fv-az883-206:05068] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fdc46aae20c]
[fv-az883-206:05068] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fdc46aae277]
[fv-az883-206:05068] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdc46aae52b]
[fv-az883-206:05068] [ 8] plumed_master(+0x14274)[0x5606cd753274]
[fv-az883-206:05068] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdc46629d90]
[fv-az883-206:05068] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdc46629e40]
[fv-az883-206:05068] [11] plumed_master(+0x14ed5)[0x5606cd753ed5]
[fv-az883-206:05068] *** End of error message ***
</pre>
{% endraw %}

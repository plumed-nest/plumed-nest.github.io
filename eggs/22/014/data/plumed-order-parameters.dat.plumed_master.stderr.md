**Project ID:** [plumID:22.014]({{ '/' | absolute_url }}eggs/22/014/)  
Stderr for source:  plumed-order-parameters.dat   
Download: [zipped raw stdout](plumed-order-parameters.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-order-parameters.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
PairEntropies.0Hxzpo.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1260) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_VERSION="2.10.0-dev" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh PairEntropies.cpp

[fv-az985-228:68596] *** Process received signal ***
[fv-az985-228:68596] Signal: Aborted (6)
[fv-az985-228:68596] Signal code:  (-6)
[fv-az985-228:68596] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fda95642520]
[fv-az985-228:68596] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fda956969fc]
[fv-az985-228:68596] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fda95642476]
[fv-az985-228:68596] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fda956287f3]
[fv-az985-228:68596] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fda95aa4f26]
[fv-az985-228:68596] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fda95ab6d9c]
[fv-az985-228:68596] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fda95ab6e07]
[fv-az985-228:68596] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fda95ab70bb]
[fv-az985-228:68596] [ 8] plumed_master(+0x12e7f)[0x557929134e7f]
[fv-az985-228:68596] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fda95629d90]
[fv-az985-228:68596] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fda95629e40]
[fv-az985-228:68596] [11] plumed_master(+0x13115)[0x557929135115]
[fv-az985-228:68596] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.c3WJtY.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1260) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_VERSION="2.10.0-dev" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh ../../../RefCV.cpp

[fv-az1535-957:71674] *** Process received signal ***
[fv-az1535-957:71674] Signal: Aborted (6)
[fv-az1535-957:71674] Signal code:  (-6)
[fv-az1535-957:71674] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc6ccc42520]
[fv-az1535-957:71674] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc6ccc969fc]
[fv-az1535-957:71674] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc6ccc42476]
[fv-az1535-957:71674] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc6ccc287f3]
[fv-az1535-957:71674] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fc6cd0a4f26]
[fv-az1535-957:71674] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fc6cd0b6d9c]
[fv-az1535-957:71674] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fc6cd0b6e07]
[fv-az1535-957:71674] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc6cd0b70bb]
[fv-az1535-957:71674] [ 8] plumed_master(+0x12e7f)[0x55b9932dce7f]
[fv-az1535-957:71674] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc6ccc29d90]
[fv-az1535-957:71674] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc6ccc29e40]
[fv-az1535-957:71674] [11] plumed_master(+0x13115)[0x55b9932dd115]
[fv-az1535-957:71674] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.JOwiAs.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1260) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_VERSION="2.10.0-dev" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh ../../../../../RefCV.cpp

[fv-az1535-957:71336] *** Process received signal ***
[fv-az1535-957:71336] Signal: Aborted (6)
[fv-az1535-957:71336] Signal code:  (-6)
[fv-az1535-957:71336] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8104842520]
[fv-az1535-957:71336] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f81048969fc]
[fv-az1535-957:71336] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8104842476]
[fv-az1535-957:71336] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f81048287f3]
[fv-az1535-957:71336] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f8104ca4f26]
[fv-az1535-957:71336] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f8104cb6d9c]
[fv-az1535-957:71336] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f8104cb6e07]
[fv-az1535-957:71336] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8104cb70bb]
[fv-az1535-957:71336] [ 8] plumed_master(+0x12e7f)[0x5630e1151e7f]
[fv-az1535-957:71336] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8104829d90]
[fv-az1535-957:71336] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8104829e40]
[fv-az1535-957:71336] [11] plumed_master(+0x13115)[0x5630e1152115]
[fv-az1535-957:71336] *** End of error message ***
</pre>
{% endraw %}

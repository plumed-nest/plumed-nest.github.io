**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.Qhb9tl.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1260) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_VERSION="2.10.0-dev" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh ../../../../../RefCV.cpp

[fv-az1535-957:71222] *** Process received signal ***
[fv-az1535-957:71222] Signal: Aborted (6)
[fv-az1535-957:71222] Signal code:  (-6)
[fv-az1535-957:71222] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7facaba42520]
[fv-az1535-957:71222] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7facaba969fc]
[fv-az1535-957:71222] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7facaba42476]
[fv-az1535-957:71222] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7facaba287f3]
[fv-az1535-957:71222] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7facabea4f26]
[fv-az1535-957:71222] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7facabeb6d9c]
[fv-az1535-957:71222] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7facabeb6e07]
[fv-az1535-957:71222] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7facabeb70bb]
[fv-az1535-957:71222] [ 8] plumed_master(+0x12e7f)[0x5585ef469e7f]
[fv-az1535-957:71222] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7facaba29d90]
[fv-az1535-957:71222] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7facaba29e40]
[fv-az1535-957:71222] [11] plumed_master(+0x13115)[0x5585ef46a115]
[fv-az1535-957:71222] *** End of error message ***
</pre>
{% endraw %}

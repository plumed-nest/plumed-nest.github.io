**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.DpSG9N.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1260) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_VERSION="2.10.0-dev" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh ../../../../../RefCV.cpp

[fv-az1535-957:71279] *** Process received signal ***
[fv-az1535-957:71279] Signal: Aborted (6)
[fv-az1535-957:71279] Signal code:  (-6)
[fv-az1535-957:71279] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fecca442520]
[fv-az1535-957:71279] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fecca4969fc]
[fv-az1535-957:71279] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fecca442476]
[fv-az1535-957:71279] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fecca4287f3]
[fv-az1535-957:71279] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fecca8a4f26]
[fv-az1535-957:71279] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fecca8b6d9c]
[fv-az1535-957:71279] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fecca8b6e07]
[fv-az1535-957:71279] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fecca8b70bb]
[fv-az1535-957:71279] [ 8] plumed_master(+0x12e7f)[0x55f258338e7f]
[fv-az1535-957:71279] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fecca429d90]
[fv-az1535-957:71279] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fecca429e40]
[fv-az1535-957:71279] [11] plumed_master(+0x13115)[0x55f258339115]
[fv-az1535-957:71279] *** End of error message ***
</pre>
{% endraw %}

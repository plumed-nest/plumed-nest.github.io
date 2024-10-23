**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.fptrdP.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[fv-az1215-275:10371] *** Process received signal ***
[fv-az1215-275:10371] Signal: Aborted (6)
[fv-az1215-275:10371] Signal code:  (-6)
[fv-az1215-275:10371] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fab2a042520]
[fv-az1215-275:10371] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fab2a0969fc]
[fv-az1215-275:10371] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fab2a042476]
[fv-az1215-275:10371] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fab2a0287f3]
[fv-az1215-275:10371] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fab2a4a2b9e]
[fv-az1215-275:10371] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fab2a4ae20c]
[fv-az1215-275:10371] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fab2a4ae277]
[fv-az1215-275:10371] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fab2a4ae52b]
[fv-az1215-275:10371] [ 8] plumed_master(+0x14254)[0x560d0a0e4254]
[fv-az1215-275:10371] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fab2a029d90]
[fv-az1215-275:10371] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fab2a029e40]
[fv-az1215-275:10371] [11] plumed_master(+0x14eb5)[0x560d0a0e4eb5]
[fv-az1215-275:10371] *** End of error message ***
</pre>
{% endraw %}

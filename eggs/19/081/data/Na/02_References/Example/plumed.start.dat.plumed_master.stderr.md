**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.xT332G.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[fv-az1215-275:10208] *** Process received signal ***
[fv-az1215-275:10208] Signal: Aborted (6)
[fv-az1215-275:10208] Signal code:  (-6)
[fv-az1215-275:10208] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc48d842520]
[fv-az1215-275:10208] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc48d8969fc]
[fv-az1215-275:10208] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc48d842476]
[fv-az1215-275:10208] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc48d8287f3]
[fv-az1215-275:10208] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc48dca2b9e]
[fv-az1215-275:10208] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc48dcae20c]
[fv-az1215-275:10208] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc48dcae277]
[fv-az1215-275:10208] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc48dcae52b]
[fv-az1215-275:10208] [ 8] plumed_master(+0x14254)[0x5589b2c52254]
[fv-az1215-275:10208] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc48d829d90]
[fv-az1215-275:10208] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc48d829e40]
[fv-az1215-275:10208] [11] plumed_master(+0x14eb5)[0x5589b2c52eb5]
[fv-az1215-275:10208] *** End of error message ***
</pre>
{% endraw %}

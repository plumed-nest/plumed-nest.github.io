**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.XnPXJ3.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az1215-275:10279] *** Process received signal ***
[fv-az1215-275:10279] Signal: Aborted (6)
[fv-az1215-275:10279] Signal code:  (-6)
[fv-az1215-275:10279] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f95d0642520]
[fv-az1215-275:10279] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f95d06969fc]
[fv-az1215-275:10279] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f95d0642476]
[fv-az1215-275:10279] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f95d06287f3]
[fv-az1215-275:10279] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f95d0aa2b9e]
[fv-az1215-275:10279] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f95d0aae20c]
[fv-az1215-275:10279] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f95d0aae277]
[fv-az1215-275:10279] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f95d0aae52b]
[fv-az1215-275:10279] [ 8] plumed(+0x14254)[0x560694a6a254]
[fv-az1215-275:10279] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f95d0629d90]
[fv-az1215-275:10279] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f95d0629e40]
[fv-az1215-275:10279] [11] plumed(+0x14eb5)[0x560694a6aeb5]
[fv-az1215-275:10279] *** End of error message ***
</pre>
{% endraw %}

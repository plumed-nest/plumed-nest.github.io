**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.aqTgb6.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az1215-275:10346] *** Process received signal ***
[fv-az1215-275:10346] Signal: Aborted (6)
[fv-az1215-275:10346] Signal code:  (-6)
[fv-az1215-275:10346] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8c06642520]
[fv-az1215-275:10346] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8c066969fc]
[fv-az1215-275:10346] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8c06642476]
[fv-az1215-275:10346] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8c066287f3]
[fv-az1215-275:10346] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f8c06aa2b9e]
[fv-az1215-275:10346] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f8c06aae20c]
[fv-az1215-275:10346] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f8c06aae277]
[fv-az1215-275:10346] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8c06aae52b]
[fv-az1215-275:10346] [ 8] plumed(+0x14254)[0x559b21b84254]
[fv-az1215-275:10346] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8c06629d90]
[fv-az1215-275:10346] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8c06629e40]
[fv-az1215-275:10346] [11] plumed(+0x14eb5)[0x559b21b84eb5]
[fv-az1215-275:10346] *** End of error message ***
</pre>
{% endraw %}

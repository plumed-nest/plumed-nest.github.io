**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.LGygUD.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[fv-az1215-275:09590] *** Process received signal ***
[fv-az1215-275:09590] Signal: Aborted (6)
[fv-az1215-275:09590] Signal code:  (-6)
[fv-az1215-275:09590] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5299a42520]
[fv-az1215-275:09590] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5299a969fc]
[fv-az1215-275:09590] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5299a42476]
[fv-az1215-275:09590] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5299a287f3]
[fv-az1215-275:09590] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5299ea2b9e]
[fv-az1215-275:09590] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5299eae20c]
[fv-az1215-275:09590] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5299eae277]
[fv-az1215-275:09590] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5299eae52b]
[fv-az1215-275:09590] [ 8] plumed_master(+0x14254)[0x559df19ab254]
[fv-az1215-275:09590] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5299a29d90]
[fv-az1215-275:09590] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5299a29e40]
[fv-az1215-275:09590] [11] plumed_master(+0x14eb5)[0x559df19abeb5]
[fv-az1215-275:09590] *** End of error message ***
</pre>
{% endraw %}

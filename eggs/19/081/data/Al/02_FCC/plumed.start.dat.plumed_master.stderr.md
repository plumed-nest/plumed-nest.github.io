**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.v1ByBK.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0-dev.so ../../RefCV.cpp

[fv-az1567-223:08740] *** Process received signal ***
[fv-az1567-223:08740] Signal: Aborted (6)
[fv-az1567-223:08740] Signal code:  (-6)
[fv-az1567-223:08740] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8ae2642520]
[fv-az1567-223:08740] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8ae26969fc]
[fv-az1567-223:08740] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8ae2642476]
[fv-az1567-223:08740] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8ae26287f3]
[fv-az1567-223:08740] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f8ae2aa2b9e]
[fv-az1567-223:08740] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f8ae2aae20c]
[fv-az1567-223:08740] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f8ae2aae277]
[fv-az1567-223:08740] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8ae2aae52b]
[fv-az1567-223:08740] [ 8] plumed_master(+0x14274)[0x55eb21194274]
[fv-az1567-223:08740] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8ae2629d90]
[fv-az1567-223:08740] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8ae2629e40]
[fv-az1567-223:08740] [11] plumed_master(+0x14ed5)[0x55eb21194ed5]
[fv-az1567-223:08740] *** End of error message ***
</pre>
{% endraw %}

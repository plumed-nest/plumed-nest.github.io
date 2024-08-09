**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.oRk7fQ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0-dev.so ../../RefCV.cpp

[fv-az1567-223:08860] *** Process received signal ***
[fv-az1567-223:08860] Signal: Aborted (6)
[fv-az1567-223:08860] Signal code:  (-6)
[fv-az1567-223:08860] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f07f7a42520]
[fv-az1567-223:08860] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f07f7a969fc]
[fv-az1567-223:08860] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f07f7a42476]
[fv-az1567-223:08860] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f07f7a287f3]
[fv-az1567-223:08860] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f07f7ea2b9e]
[fv-az1567-223:08860] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f07f7eae20c]
[fv-az1567-223:08860] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f07f7eae277]
[fv-az1567-223:08860] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f07f7eae52b]
[fv-az1567-223:08860] [ 8] plumed_master(+0x14274)[0x5589ffd60274]
[fv-az1567-223:08860] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f07f7a29d90]
[fv-az1567-223:08860] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f07f7a29e40]
[fv-az1567-223:08860] [11] plumed_master(+0x14ed5)[0x5589ffd60ed5]
[fv-az1567-223:08860] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.XrY2rf.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0-dev.so ../../RefCV.cpp

[fv-az1567-223:08798] *** Process received signal ***
[fv-az1567-223:08798] Signal: Aborted (6)
[fv-az1567-223:08798] Signal code:  (-6)
[fv-az1567-223:08798] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7efd2a842520]
[fv-az1567-223:08798] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7efd2a8969fc]
[fv-az1567-223:08798] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7efd2a842476]
[fv-az1567-223:08798] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7efd2a8287f3]
[fv-az1567-223:08798] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7efd2aca2b9e]
[fv-az1567-223:08798] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7efd2acae20c]
[fv-az1567-223:08798] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7efd2acae277]
[fv-az1567-223:08798] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7efd2acae52b]
[fv-az1567-223:08798] [ 8] plumed_master(+0x14274)[0x5605d41eb274]
[fv-az1567-223:08798] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7efd2a829d90]
[fv-az1567-223:08798] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7efd2a829e40]
[fv-az1567-223:08798] [11] plumed_master(+0x14ed5)[0x5605d41ebed5]
[fv-az1567-223:08798] *** End of error message ***
</pre>
{% endraw %}

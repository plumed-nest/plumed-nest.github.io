**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.kecWXn.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[fv-az1112-175:68590] *** Process received signal ***
[fv-az1112-175:68590] Signal: Aborted (6)
[fv-az1112-175:68590] Signal code:  (-6)
[fv-az1112-175:68590] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2c42445330]
[fv-az1112-175:68590] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2c4249eb2c]
[fv-az1112-175:68590] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2c4244527e]
[fv-az1112-175:68590] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2c424288ff]
[fv-az1112-175:68590] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2c428a5ff5]
[fv-az1112-175:68590] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2c428bb0da]
[fv-az1112-175:68590] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2c428a5a55]
[fv-az1112-175:68590] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2c428a5a6f]
[fv-az1112-175:68590] [ 8] plumed_master(+0x146dd)[0x55d60f6946dd]
[fv-az1112-175:68590] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2c4242a1ca]
[fv-az1112-175:68590] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2c4242a28b]
[fv-az1112-175:68590] [11] plumed_master(+0x15365)[0x55d60f695365]
[fv-az1112-175:68590] *** End of error message ***
</pre>
{% endraw %}

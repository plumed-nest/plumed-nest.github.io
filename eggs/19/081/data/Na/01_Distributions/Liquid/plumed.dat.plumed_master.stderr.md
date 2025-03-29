**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.0q13qj.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[fv-az1344-582:67194] *** Process received signal ***
[fv-az1344-582:67194] Signal: Aborted (6)
[fv-az1344-582:67194] Signal code:  (-6)
[fv-az1344-582:67194] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa9c5e45330]
[fv-az1344-582:67194] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa9c5e9eb2c]
[fv-az1344-582:67194] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa9c5e4527e]
[fv-az1344-582:67194] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa9c5e288ff]
[fv-az1344-582:67194] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa9c62a5ff5]
[fv-az1344-582:67194] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa9c62bb0da]
[fv-az1344-582:67194] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa9c62a5a55]
[fv-az1344-582:67194] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa9c62a5a6f]
[fv-az1344-582:67194] [ 8] plumed_master(+0x146dd)[0x559aa66a06dd]
[fv-az1344-582:67194] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa9c5e2a1ca]
[fv-az1344-582:67194] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa9c5e2a28b]
[fv-az1344-582:67194] [11] plumed_master(+0x15365)[0x559aa66a1365]
[fv-az1344-582:67194] *** End of error message ***
</pre>
{% endraw %}

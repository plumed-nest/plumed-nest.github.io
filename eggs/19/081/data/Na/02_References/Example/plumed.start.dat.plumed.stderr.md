**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.SQfYs7.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[fv-az1112-175:69281] *** Process received signal ***
[fv-az1112-175:69281] Signal: Aborted (6)
[fv-az1112-175:69281] Signal code:  (-6)
[fv-az1112-175:69281] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc610645330]
[fv-az1112-175:69281] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc61069eb2c]
[fv-az1112-175:69281] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc61064527e]
[fv-az1112-175:69281] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6106288ff]
[fv-az1112-175:69281] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc610aa5ff5]
[fv-az1112-175:69281] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc610abb0da]
[fv-az1112-175:69281] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc610aa5a55]
[fv-az1112-175:69281] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc610aa5a6f]
[fv-az1112-175:69281] [ 8] plumed(+0x146dd)[0x563a0f90b6dd]
[fv-az1112-175:69281] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc61062a1ca]
[fv-az1112-175:69281] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc61062a28b]
[fv-az1112-175:69281] [11] plumed(+0x15365)[0x563a0f90c365]
[fv-az1112-175:69281] *** End of error message ***
</pre>
{% endraw %}

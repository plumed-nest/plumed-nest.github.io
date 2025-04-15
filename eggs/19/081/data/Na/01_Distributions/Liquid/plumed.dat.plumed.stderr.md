**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.OPP7eK.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[fv-az1277-646:68847] *** Process received signal ***
[fv-az1277-646:68847] Signal: Aborted (6)
[fv-az1277-646:68847] Signal code:  (-6)
[fv-az1277-646:68847] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe5e445330]
[fv-az1277-646:68847] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe5e49eb2c]
[fv-az1277-646:68847] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe5e44527e]
[fv-az1277-646:68847] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe5e4288ff]
[fv-az1277-646:68847] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe5e8a5ff5]
[fv-az1277-646:68847] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe5e8bb0da]
[fv-az1277-646:68847] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe5e8a5a55]
[fv-az1277-646:68847] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe5e8a5a6f]
[fv-az1277-646:68847] [ 8] plumed(+0x146dd)[0x55a3adeab6dd]
[fv-az1277-646:68847] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe5e42a1ca]
[fv-az1277-646:68847] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe5e42a28b]
[fv-az1277-646:68847] [11] plumed(+0x15365)[0x55a3adeac365]
[fv-az1277-646:68847] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.PFg6uV.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[fv-az1277-646:69055] *** Process received signal ***
[fv-az1277-646:69055] Signal: Aborted (6)
[fv-az1277-646:69055] Signal code:  (-6)
[fv-az1277-646:69055] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f893a045330]
[fv-az1277-646:69055] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f893a09eb2c]
[fv-az1277-646:69055] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f893a04527e]
[fv-az1277-646:69055] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f893a0288ff]
[fv-az1277-646:69055] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f893a4a5ff5]
[fv-az1277-646:69055] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f893a4bb0da]
[fv-az1277-646:69055] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f893a4a5a55]
[fv-az1277-646:69055] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f893a4a5a6f]
[fv-az1277-646:69055] [ 8] plumed(+0x146dd)[0x56393fb156dd]
[fv-az1277-646:69055] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f893a02a1ca]
[fv-az1277-646:69055] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f893a02a28b]
[fv-az1277-646:69055] [11] plumed(+0x15365)[0x56393fb16365]
[fv-az1277-646:69055] *** End of error message ***
</pre>
{% endraw %}

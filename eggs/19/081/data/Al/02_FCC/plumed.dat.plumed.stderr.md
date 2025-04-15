**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.eaxbee.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az1277-646:68504] *** Process received signal ***
[fv-az1277-646:68504] Signal: Aborted (6)
[fv-az1277-646:68504] Signal code:  (-6)
[fv-az1277-646:68504] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7cd7645330]
[fv-az1277-646:68504] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7cd769eb2c]
[fv-az1277-646:68504] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7cd764527e]
[fv-az1277-646:68504] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7cd76288ff]
[fv-az1277-646:68504] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7cd7aa5ff5]
[fv-az1277-646:68504] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7cd7abb0da]
[fv-az1277-646:68504] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7cd7aa5a55]
[fv-az1277-646:68504] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7cd7aa5a6f]
[fv-az1277-646:68504] [ 8] plumed(+0x146dd)[0x5607235a06dd]
[fv-az1277-646:68504] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7cd762a1ca]
[fv-az1277-646:68504] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7cd762a28b]
[fv-az1277-646:68504] [11] plumed(+0x15365)[0x5607235a1365]
[fv-az1277-646:68504] *** End of error message ***
</pre>
{% endraw %}

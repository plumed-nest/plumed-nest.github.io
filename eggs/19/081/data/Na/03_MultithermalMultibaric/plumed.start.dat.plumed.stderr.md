**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.LAS7HH.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az1112-175:69492] *** Process received signal ***
[fv-az1112-175:69492] Signal: Aborted (6)
[fv-az1112-175:69492] Signal code:  (-6)
[fv-az1112-175:69492] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff4c1045330]
[fv-az1112-175:69492] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff4c109eb2c]
[fv-az1112-175:69492] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff4c104527e]
[fv-az1112-175:69492] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff4c10288ff]
[fv-az1112-175:69492] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff4c14a5ff5]
[fv-az1112-175:69492] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff4c14bb0da]
[fv-az1112-175:69492] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff4c14a5a55]
[fv-az1112-175:69492] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff4c14a5a6f]
[fv-az1112-175:69492] [ 8] plumed(+0x146dd)[0x560b719f36dd]
[fv-az1112-175:69492] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff4c102a1ca]
[fv-az1112-175:69492] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff4c102a28b]
[fv-az1112-175:69492] [11] plumed(+0x15365)[0x560b719f4365]
[fv-az1112-175:69492] *** End of error message ***
</pre>
{% endraw %}

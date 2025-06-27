**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.6xwW1f.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[pkrvmbietmlfzoi:67593] *** Process received signal ***
[pkrvmbietmlfzoi:67593] Signal: Aborted (6)
[pkrvmbietmlfzoi:67593] Signal code:  (-6)
[pkrvmbietmlfzoi:67593] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7b8e645330]
[pkrvmbietmlfzoi:67593] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7b8e69eb2c]
[pkrvmbietmlfzoi:67593] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7b8e64527e]
[pkrvmbietmlfzoi:67593] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7b8e6288ff]
[pkrvmbietmlfzoi:67593] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7b8eaa5ff5]
[pkrvmbietmlfzoi:67593] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7b8eabb0da]
[pkrvmbietmlfzoi:67593] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7b8eaa5a55]
[pkrvmbietmlfzoi:67593] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7b8eaa5a6f]
[pkrvmbietmlfzoi:67593] [ 8] plumed(+0x146dd)[0x561dac84f6dd]
[pkrvmbietmlfzoi:67593] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7b8e62a1ca]
[pkrvmbietmlfzoi:67593] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7b8e62a28b]
[pkrvmbietmlfzoi:67593] [11] plumed(+0x15365)[0x561dac850365]
[pkrvmbietmlfzoi:67593] *** End of error message ***
</pre>
{% endraw %}

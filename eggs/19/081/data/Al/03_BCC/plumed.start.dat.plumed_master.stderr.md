**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.l0GhMU.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[pkrvmbietmlfzoi:13207] *** Process received signal ***
[pkrvmbietmlfzoi:13207] Signal: Aborted (6)
[pkrvmbietmlfzoi:13207] Signal code:  (-6)
[pkrvmbietmlfzoi:13207] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3276645330]
[pkrvmbietmlfzoi:13207] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f327669eb2c]
[pkrvmbietmlfzoi:13207] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f327664527e]
[pkrvmbietmlfzoi:13207] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f32766288ff]
[pkrvmbietmlfzoi:13207] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3276aa5ff5]
[pkrvmbietmlfzoi:13207] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3276abb0da]
[pkrvmbietmlfzoi:13207] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3276aa5a55]
[pkrvmbietmlfzoi:13207] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3276aa5a6f]
[pkrvmbietmlfzoi:13207] [ 8] plumed_master(+0x146dd)[0x55b3c83536dd]
[pkrvmbietmlfzoi:13207] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f327662a1ca]
[pkrvmbietmlfzoi:13207] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f327662a28b]
[pkrvmbietmlfzoi:13207] [11] plumed_master(+0x15365)[0x55b3c8354365]
[pkrvmbietmlfzoi:13207] *** End of error message ***
</pre>
{% endraw %}

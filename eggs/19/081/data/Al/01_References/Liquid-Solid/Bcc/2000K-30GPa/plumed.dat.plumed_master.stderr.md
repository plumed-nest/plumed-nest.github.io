**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.k8XqaP.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[pkrvmbietmlfzoi:66732] *** Process received signal ***
[pkrvmbietmlfzoi:66732] Signal: Aborted (6)
[pkrvmbietmlfzoi:66732] Signal code:  (-6)
[pkrvmbietmlfzoi:66732] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f941e645330]
[pkrvmbietmlfzoi:66732] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f941e69eb2c]
[pkrvmbietmlfzoi:66732] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f941e64527e]
[pkrvmbietmlfzoi:66732] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f941e6288ff]
[pkrvmbietmlfzoi:66732] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f941eaa5ff5]
[pkrvmbietmlfzoi:66732] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f941eabb0da]
[pkrvmbietmlfzoi:66732] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f941eaa5a55]
[pkrvmbietmlfzoi:66732] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f941eaa5a6f]
[pkrvmbietmlfzoi:66732] [ 8] plumed_master(+0x146dd)[0x5616b87de6dd]
[pkrvmbietmlfzoi:66732] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f941e62a1ca]
[pkrvmbietmlfzoi:66732] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f941e62a28b]
[pkrvmbietmlfzoi:66732] [11] plumed_master(+0x15365)[0x5616b87df365]
[pkrvmbietmlfzoi:66732] *** End of error message ***
</pre>
{% endraw %}

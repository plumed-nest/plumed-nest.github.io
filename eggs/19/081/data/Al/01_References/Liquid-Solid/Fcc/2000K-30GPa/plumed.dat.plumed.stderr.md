**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.xH2CXM.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[pkrvmbietmlfzoi:66872] *** Process received signal ***
[pkrvmbietmlfzoi:66872] Signal: Aborted (6)
[pkrvmbietmlfzoi:66872] Signal code:  (-6)
[pkrvmbietmlfzoi:66872] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcfe9845330]
[pkrvmbietmlfzoi:66872] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcfe989eb2c]
[pkrvmbietmlfzoi:66872] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcfe984527e]
[pkrvmbietmlfzoi:66872] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcfe98288ff]
[pkrvmbietmlfzoi:66872] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcfe9ca5ff5]
[pkrvmbietmlfzoi:66872] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcfe9cbb0da]
[pkrvmbietmlfzoi:66872] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcfe9ca5a55]
[pkrvmbietmlfzoi:66872] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcfe9ca5a6f]
[pkrvmbietmlfzoi:66872] [ 8] plumed(+0x146dd)[0x56013597c6dd]
[pkrvmbietmlfzoi:66872] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcfe982a1ca]
[pkrvmbietmlfzoi:66872] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcfe982a28b]
[pkrvmbietmlfzoi:66872] [11] plumed(+0x15365)[0x56013597d365]
[pkrvmbietmlfzoi:66872] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.Pt8IeR.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmbietmlfzoi:12919] *** Process received signal ***
[pkrvmbietmlfzoi:12919] Signal: Aborted (6)
[pkrvmbietmlfzoi:12919] Signal code:  (-6)
[pkrvmbietmlfzoi:12919] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19de645330]
[pkrvmbietmlfzoi:12919] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19de69eb2c]
[pkrvmbietmlfzoi:12919] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19de64527e]
[pkrvmbietmlfzoi:12919] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19de6288ff]
[pkrvmbietmlfzoi:12919] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19deaa5ff5]
[pkrvmbietmlfzoi:12919] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19deabb0da]
[pkrvmbietmlfzoi:12919] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19deaa5a55]
[pkrvmbietmlfzoi:12919] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19deaa5a6f]
[pkrvmbietmlfzoi:12919] [ 8] plumed(+0x146dd)[0x561055ee26dd]
[pkrvmbietmlfzoi:12919] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19de62a1ca]
[pkrvmbietmlfzoi:12919] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19de62a28b]
[pkrvmbietmlfzoi:12919] [11] plumed(+0x15365)[0x561055ee3365]
[pkrvmbietmlfzoi:12919] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.SnjsR7.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[pkrvmpptgkbjq6m:13488] *** Process received signal ***
[pkrvmpptgkbjq6m:13488] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13488] Signal code:  (-6)
[pkrvmpptgkbjq6m:13488] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff76f845330]
[pkrvmpptgkbjq6m:13488] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff76f89eb2c]
[pkrvmpptgkbjq6m:13488] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff76f84527e]
[pkrvmpptgkbjq6m:13488] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff76f8288ff]
[pkrvmpptgkbjq6m:13488] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff76fca5ff5]
[pkrvmpptgkbjq6m:13488] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff76fcbb0da]
[pkrvmpptgkbjq6m:13488] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff76fca5a55]
[pkrvmpptgkbjq6m:13488] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff76fca5a6f]
[pkrvmpptgkbjq6m:13488] [ 8] plumed_master(+0x146dd)[0x55e207a756dd]
[pkrvmpptgkbjq6m:13488] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff76f82a1ca]
[pkrvmpptgkbjq6m:13488] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff76f82a28b]
[pkrvmpptgkbjq6m:13488] [11] plumed_master(+0x15365)[0x55e207a76365]
[pkrvmpptgkbjq6m:13488] *** End of error message ***
</pre>
{% endraw %}

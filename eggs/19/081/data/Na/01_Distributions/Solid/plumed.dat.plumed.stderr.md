**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Solid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.xMFkAv.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[pkrvm7jw40e0xgp:13220] *** Process received signal ***
[pkrvm7jw40e0xgp:13220] Signal: Aborted (6)
[pkrvm7jw40e0xgp:13220] Signal code:  (-6)
[pkrvm7jw40e0xgp:13220] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe606a45330]
[pkrvm7jw40e0xgp:13220] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe606a9eb2c]
[pkrvm7jw40e0xgp:13220] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe606a4527e]
[pkrvm7jw40e0xgp:13220] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe606a288ff]
[pkrvm7jw40e0xgp:13220] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe606ea5ff5]
[pkrvm7jw40e0xgp:13220] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe606ebb0da]
[pkrvm7jw40e0xgp:13220] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe606ea5a55]
[pkrvm7jw40e0xgp:13220] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe606ea5a6f]
[pkrvm7jw40e0xgp:13220] [ 8] plumed(+0x146dd)[0x564ea8b816dd]
[pkrvm7jw40e0xgp:13220] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe606a2a1ca]
[pkrvm7jw40e0xgp:13220] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe606a2a28b]
[pkrvm7jw40e0xgp:13220] [11] plumed(+0x15365)[0x564ea8b82365]
[pkrvm7jw40e0xgp:13220] *** End of error message ***
</pre>
{% endraw %}

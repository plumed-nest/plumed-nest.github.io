**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.VpIVqX.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[pkrvm7jw40e0xgp:13461] *** Process received signal ***
[pkrvm7jw40e0xgp:13461] Signal: Aborted (6)
[pkrvm7jw40e0xgp:13461] Signal code:  (-6)
[pkrvm7jw40e0xgp:13461] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b9b045330]
[pkrvm7jw40e0xgp:13461] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b9b09eb2c]
[pkrvm7jw40e0xgp:13461] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b9b04527e]
[pkrvm7jw40e0xgp:13461] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b9b0288ff]
[pkrvm7jw40e0xgp:13461] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b9b4a5ff5]
[pkrvm7jw40e0xgp:13461] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b9b4bb0da]
[pkrvm7jw40e0xgp:13461] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b9b4a5a55]
[pkrvm7jw40e0xgp:13461] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b9b4a5a6f]
[pkrvm7jw40e0xgp:13461] [ 8] plumed_master(+0x146dd)[0x55a3633916dd]
[pkrvm7jw40e0xgp:13461] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b9b02a1ca]
[pkrvm7jw40e0xgp:13461] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b9b02a28b]
[pkrvm7jw40e0xgp:13461] [11] plumed_master(+0x15365)[0x55a363392365]
[pkrvm7jw40e0xgp:13461] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.DsNbkS.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[fv-az790-36:68703] *** Process received signal ***
[fv-az790-36:68703] Signal: Aborted (6)
[fv-az790-36:68703] Signal code:  (-6)
[fv-az790-36:68703] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f261b645330]
[fv-az790-36:68703] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f261b69eb2c]
[fv-az790-36:68703] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f261b64527e]
[fv-az790-36:68703] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f261b6288ff]
[fv-az790-36:68703] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f261baa5ff5]
[fv-az790-36:68703] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f261babb0da]
[fv-az790-36:68703] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f261baa5a55]
[fv-az790-36:68703] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f261baa5a6f]
[fv-az790-36:68703] [ 8] plumed_master(+0x146dd)[0x55b6d21a46dd]
[fv-az790-36:68703] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f261b62a1ca]
[fv-az790-36:68703] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f261b62a28b]
[fv-az790-36:68703] [11] plumed_master(+0x15365)[0x55b6d21a5365]
[fv-az790-36:68703] *** End of error message ***
</pre>
{% endraw %}

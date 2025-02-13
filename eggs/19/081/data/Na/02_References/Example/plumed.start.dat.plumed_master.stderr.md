**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.QqcTWs.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[fv-az1046-619:10974] *** Process received signal ***
[fv-az1046-619:10974] Signal: Aborted (6)
[fv-az1046-619:10974] Signal code:  (-6)
[fv-az1046-619:10974] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f074f845330]
[fv-az1046-619:10974] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f074f89eb2c]
[fv-az1046-619:10974] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f074f84527e]
[fv-az1046-619:10974] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f074f8288ff]
[fv-az1046-619:10974] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f074fca5ff5]
[fv-az1046-619:10974] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f074fcbb0da]
[fv-az1046-619:10974] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f074fca5a55]
[fv-az1046-619:10974] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f074fca5a6f]
[fv-az1046-619:10974] [ 8] plumed_master(+0x146dd)[0x556737f786dd]
[fv-az1046-619:10974] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f074f82a1ca]
[fv-az1046-619:10974] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f074f82a28b]
[fv-az1046-619:10974] [11] plumed_master(+0x15365)[0x556737f79365]
[fv-az1046-619:10974] *** End of error message ***
</pre>
{% endraw %}

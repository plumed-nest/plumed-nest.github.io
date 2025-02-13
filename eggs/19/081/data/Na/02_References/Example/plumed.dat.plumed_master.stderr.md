**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.8oC07i.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[fv-az1046-619:10889] *** Process received signal ***
[fv-az1046-619:10889] Signal: Aborted (6)
[fv-az1046-619:10889] Signal code:  (-6)
[fv-az1046-619:10889] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb88ae45330]
[fv-az1046-619:10889] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb88ae9eb2c]
[fv-az1046-619:10889] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb88ae4527e]
[fv-az1046-619:10889] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb88ae288ff]
[fv-az1046-619:10889] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb88b2a5ff5]
[fv-az1046-619:10889] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb88b2bb0da]
[fv-az1046-619:10889] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb88b2a5a55]
[fv-az1046-619:10889] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb88b2a5a6f]
[fv-az1046-619:10889] [ 8] plumed_master(+0x146dd)[0x559b422016dd]
[fv-az1046-619:10889] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb88ae2a1ca]
[fv-az1046-619:10889] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb88ae2a28b]
[fv-az1046-619:10889] [11] plumed_master(+0x15365)[0x559b42202365]
[fv-az1046-619:10889] *** End of error message ***
</pre>
{% endraw %}

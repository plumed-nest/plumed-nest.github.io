**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.5rllsj.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[fv-az790-36:68275] *** Process received signal ***
[fv-az790-36:68275] Signal: Aborted (6)
[fv-az790-36:68275] Signal code:  (-6)
[fv-az790-36:68275] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f36d3c45330]
[fv-az790-36:68275] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f36d3c9eb2c]
[fv-az790-36:68275] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f36d3c4527e]
[fv-az790-36:68275] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f36d3c288ff]
[fv-az790-36:68275] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f36d40a5ff5]
[fv-az790-36:68275] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f36d40bb0da]
[fv-az790-36:68275] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f36d40a5a55]
[fv-az790-36:68275] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f36d40a5a6f]
[fv-az790-36:68275] [ 8] plumed_master(+0x146dd)[0x55d19adee6dd]
[fv-az790-36:68275] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f36d3c2a1ca]
[fv-az790-36:68275] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f36d3c2a28b]
[fv-az790-36:68275] [11] plumed_master(+0x15365)[0x55d19adef365]
[fv-az790-36:68275] *** End of error message ***
</pre>
{% endraw %}

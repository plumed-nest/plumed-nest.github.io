**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.QS9Zw0.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[fv-az790-36:68998] *** Process received signal ***
[fv-az790-36:68998] Signal: Aborted (6)
[fv-az790-36:68998] Signal code:  (-6)
[fv-az790-36:68998] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa4f7045330]
[fv-az790-36:68998] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa4f709eb2c]
[fv-az790-36:68998] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa4f704527e]
[fv-az790-36:68998] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4f70288ff]
[fv-az790-36:68998] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4f74a5ff5]
[fv-az790-36:68998] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4f74bb0da]
[fv-az790-36:68998] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4f74a5a55]
[fv-az790-36:68998] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4f74a5a6f]
[fv-az790-36:68998] [ 8] plumed_master(+0x146dd)[0x56022a0db6dd]
[fv-az790-36:68998] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa4f702a1ca]
[fv-az790-36:68998] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa4f702a28b]
[fv-az790-36:68998] [11] plumed_master(+0x15365)[0x56022a0dc365]
[fv-az790-36:68998] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.1HhpAl.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[fv-az805-507:09869] *** Process received signal ***
[fv-az805-507:09869] Signal: Aborted (6)
[fv-az805-507:09869] Signal code:  (-6)
[fv-az805-507:09869] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1b58845330]
[fv-az805-507:09869] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1b5889eb2c]
[fv-az805-507:09869] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1b5884527e]
[fv-az805-507:09869] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1b588288ff]
[fv-az805-507:09869] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1b58ca5ff5]
[fv-az805-507:09869] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1b58cbb0da]
[fv-az805-507:09869] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1b58ca5a55]
[fv-az805-507:09869] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1b58ca5a6f]
[fv-az805-507:09869] [ 8] plumed_master(+0x146dd)[0x55e31a2c86dd]
[fv-az805-507:09869] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1b5882a1ca]
[fv-az805-507:09869] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1b5882a28b]
[fv-az805-507:09869] [11] plumed_master(+0x15365)[0x55e31a2c9365]
[fv-az805-507:09869] *** End of error message ***
</pre>
{% endraw %}

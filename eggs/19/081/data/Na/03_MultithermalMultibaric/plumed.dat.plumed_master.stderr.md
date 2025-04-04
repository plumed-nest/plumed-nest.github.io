**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.j4XkZ8.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[fv-az805-507:10377] *** Process received signal ***
[fv-az805-507:10377] Signal: Aborted (6)
[fv-az805-507:10377] Signal code:  (-6)
[fv-az805-507:10377] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e05645330]
[fv-az805-507:10377] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e0569eb2c]
[fv-az805-507:10377] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e0564527e]
[fv-az805-507:10377] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e056288ff]
[fv-az805-507:10377] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e05aa5ff5]
[fv-az805-507:10377] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e05abb0da]
[fv-az805-507:10377] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e05aa5a55]
[fv-az805-507:10377] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e05aa5a6f]
[fv-az805-507:10377] [ 8] plumed_master(+0x146dd)[0x5586481ec6dd]
[fv-az805-507:10377] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e0562a1ca]
[fv-az805-507:10377] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e0562a28b]
[fv-az805-507:10377] [11] plumed_master(+0x15365)[0x5586481ed365]
[fv-az805-507:10377] *** End of error message ***
</pre>
{% endraw %}

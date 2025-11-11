**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.T1j5SB.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[runnervmw9dnm:10750] *** Process received signal ***
[runnervmw9dnm:10750] Signal: Aborted (6)
[runnervmw9dnm:10750] Signal code:  (-6)
[runnervmw9dnm:10750] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5f32645330]
[runnervmw9dnm:10750] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5f3269eb2c]
[runnervmw9dnm:10750] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5f3264527e]
[runnervmw9dnm:10750] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5f326288ff]
[runnervmw9dnm:10750] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5f32aa5ff5]
[runnervmw9dnm:10750] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5f32abb0da]
[runnervmw9dnm:10750] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5f32aa5a55]
[runnervmw9dnm:10750] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5f32aa5a6f]
[runnervmw9dnm:10750] [ 8] plumed_master(+0x146dd)[0x55f25c2686dd]
[runnervmw9dnm:10750] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5f3262a1ca]
[runnervmw9dnm:10750] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5f3262a28b]
[runnervmw9dnm:10750] [11] plumed_master(+0x15365)[0x55f25c269365]
[runnervmw9dnm:10750] *** End of error message ***
</pre>
{% endraw %}

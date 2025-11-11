**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Solid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.AYyiNk.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[runnervmw9dnm:10419] *** Process received signal ***
[runnervmw9dnm:10419] Signal: Aborted (6)
[runnervmw9dnm:10419] Signal code:  (-6)
[runnervmw9dnm:10419] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0106845330]
[runnervmw9dnm:10419] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f010689eb2c]
[runnervmw9dnm:10419] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f010684527e]
[runnervmw9dnm:10419] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01068288ff]
[runnervmw9dnm:10419] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0106ca5ff5]
[runnervmw9dnm:10419] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0106cbb0da]
[runnervmw9dnm:10419] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0106ca5a55]
[runnervmw9dnm:10419] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0106ca5a6f]
[runnervmw9dnm:10419] [ 8] plumed_master(+0x146dd)[0x55a1ab43f6dd]
[runnervmw9dnm:10419] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f010682a1ca]
[runnervmw9dnm:10419] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f010682a28b]
[runnervmw9dnm:10419] [11] plumed_master(+0x15365)[0x55a1ab440365]
[runnervmw9dnm:10419] *** End of error message ***
</pre>
{% endraw %}

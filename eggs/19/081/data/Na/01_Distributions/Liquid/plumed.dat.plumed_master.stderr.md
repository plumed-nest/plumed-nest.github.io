**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.iNUI1G.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[runnervmmklqx:11522] *** Process received signal ***
[runnervmmklqx:11522] Signal: Aborted (6)
[runnervmmklqx:11522] Signal code:  (-6)
[runnervmmklqx:11522] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f03ed645330]
[runnervmmklqx:11522] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f03ed69eb2c]
[runnervmmklqx:11522] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f03ed64527e]
[runnervmmklqx:11522] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03ed6288ff]
[runnervmmklqx:11522] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03edaa5ff5]
[runnervmmklqx:11522] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03edabb0da]
[runnervmmklqx:11522] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03edaa5a55]
[runnervmmklqx:11522] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03edaa5a6f]
[runnervmmklqx:11522] [ 8] plumed_master(+0x146dd)[0x55b114b556dd]
[runnervmmklqx:11522] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f03ed62a1ca]
[runnervmmklqx:11522] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f03ed62a28b]
[runnervmmklqx:11522] [11] plumed_master(+0x15365)[0x55b114b56365]
[runnervmmklqx:11522] *** End of error message ***
</pre>
{% endraw %}

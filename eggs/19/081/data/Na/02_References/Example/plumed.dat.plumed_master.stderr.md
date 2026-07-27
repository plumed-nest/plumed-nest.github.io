**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.8ojJBQ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[runnervmvrwv9:10777] *** Process received signal ***
[runnervmvrwv9:10777] Signal: Aborted (6)
[runnervmvrwv9:10777] Signal code:  (-6)
[runnervmvrwv9:10777] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0dce045330]
[runnervmvrwv9:10777] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0dce09eb2c]
[runnervmvrwv9:10777] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0dce04527e]
[runnervmvrwv9:10777] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0dce0288ff]
[runnervmvrwv9:10777] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0dce4a5ff5]
[runnervmvrwv9:10777] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0dce4bb0da]
[runnervmvrwv9:10777] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0dce4a5a55]
[runnervmvrwv9:10777] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0dce4a5a6f]
[runnervmvrwv9:10777] [ 8] plumed_master(+0x146dd)[0x55b6e6e556dd]
[runnervmvrwv9:10777] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0dce02a1ca]
[runnervmvrwv9:10777] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0dce02a28b]
[runnervmvrwv9:10777] [11] plumed_master(+0x15365)[0x55b6e6e56365]
[runnervmvrwv9:10777] *** End of error message ***
</pre>
{% endraw %}

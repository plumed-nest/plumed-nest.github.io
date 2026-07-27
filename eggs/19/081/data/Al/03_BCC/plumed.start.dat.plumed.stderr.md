**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.v8190J.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.1.so ../../RefCV.cpp

[runnervmvrwv9:10436] *** Process received signal ***
[runnervmvrwv9:10436] Signal: Aborted (6)
[runnervmvrwv9:10436] Signal code:  (-6)
[runnervmvrwv9:10436] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9cac445330]
[runnervmvrwv9:10436] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9cac49eb2c]
[runnervmvrwv9:10436] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9cac44527e]
[runnervmvrwv9:10436] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9cac4288ff]
[runnervmvrwv9:10436] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9cac8a5ff5]
[runnervmvrwv9:10436] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9cac8bb0da]
[runnervmvrwv9:10436] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9cac8a5a55]
[runnervmvrwv9:10436] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9cac8a5a6f]
[runnervmvrwv9:10436] [ 8] plumed(+0x146dd)[0x5622a46b36dd]
[runnervmvrwv9:10436] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9cac42a1ca]
[runnervmvrwv9:10436] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9cac42a28b]
[runnervmvrwv9:10436] [11] plumed(+0x15365)[0x5622a46b4365]
[runnervmvrwv9:10436] *** End of error message ***
</pre>
{% endraw %}

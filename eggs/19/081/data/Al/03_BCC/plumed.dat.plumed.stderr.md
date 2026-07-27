**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.W4APYJ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.1.so ../../RefCV.cpp

[runnervmvrwv9:10351] *** Process received signal ***
[runnervmvrwv9:10351] Signal: Aborted (6)
[runnervmvrwv9:10351] Signal code:  (-6)
[runnervmvrwv9:10351] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa95f045330]
[runnervmvrwv9:10351] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa95f09eb2c]
[runnervmvrwv9:10351] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa95f04527e]
[runnervmvrwv9:10351] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa95f0288ff]
[runnervmvrwv9:10351] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa95f4a5ff5]
[runnervmvrwv9:10351] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa95f4bb0da]
[runnervmvrwv9:10351] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa95f4a5a55]
[runnervmvrwv9:10351] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa95f4a5a6f]
[runnervmvrwv9:10351] [ 8] plumed(+0x146dd)[0x5652fe1866dd]
[runnervmvrwv9:10351] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa95f02a1ca]
[runnervmvrwv9:10351] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa95f02a28b]
[runnervmvrwv9:10351] [11] plumed(+0x15365)[0x5652fe187365]
[runnervmvrwv9:10351] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.CyffBh.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervmmklqx:11318] *** Process received signal ***
[runnervmmklqx:11318] Signal: Aborted (6)
[runnervmmklqx:11318] Signal code:  (-6)
[runnervmmklqx:11318] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8df5445330]
[runnervmmklqx:11318] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8df549eb2c]
[runnervmmklqx:11318] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8df544527e]
[runnervmmklqx:11318] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8df54288ff]
[runnervmmklqx:11318] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8df58a5ff5]
[runnervmmklqx:11318] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8df58bb0da]
[runnervmmklqx:11318] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8df58a5a55]
[runnervmmklqx:11318] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8df58a5a6f]
[runnervmmklqx:11318] [ 8] plumed(+0x146dd)[0x5592fdbc86dd]
[runnervmmklqx:11318] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8df542a1ca]
[runnervmmklqx:11318] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8df542a28b]
[runnervmmklqx:11318] [11] plumed(+0x15365)[0x5592fdbc9365]
[runnervmmklqx:11318] *** End of error message ***
</pre>
{% endraw %}

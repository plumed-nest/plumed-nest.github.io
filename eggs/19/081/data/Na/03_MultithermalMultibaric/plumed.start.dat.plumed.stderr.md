**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.jW8Ovc.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervmmklqx:12010] *** Process received signal ***
[runnervmmklqx:12010] Signal: Aborted (6)
[runnervmmklqx:12010] Signal code:  (-6)
[runnervmmklqx:12010] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1bd8245330]
[runnervmmklqx:12010] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1bd829eb2c]
[runnervmmklqx:12010] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1bd824527e]
[runnervmmklqx:12010] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1bd82288ff]
[runnervmmklqx:12010] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1bd86a5ff5]
[runnervmmklqx:12010] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1bd86bb0da]
[runnervmmklqx:12010] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1bd86a5a55]
[runnervmmklqx:12010] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1bd86a5a6f]
[runnervmmklqx:12010] [ 8] plumed(+0x146dd)[0x55b4220ac6dd]
[runnervmmklqx:12010] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1bd822a1ca]
[runnervmmklqx:12010] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1bd822a28b]
[runnervmmklqx:12010] [11] plumed(+0x15365)[0x55b4220ad365]
[runnervmmklqx:12010] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.apWnsr.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervmmklqx:11403] *** Process received signal ***
[runnervmmklqx:11403] Signal: Aborted (6)
[runnervmmklqx:11403] Signal code:  (-6)
[runnervmmklqx:11403] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff363445330]
[runnervmmklqx:11403] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff36349eb2c]
[runnervmmklqx:11403] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff36344527e]
[runnervmmklqx:11403] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff3634288ff]
[runnervmmklqx:11403] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff3638a5ff5]
[runnervmmklqx:11403] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff3638bb0da]
[runnervmmklqx:11403] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff3638a5a55]
[runnervmmklqx:11403] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff3638a5a6f]
[runnervmmklqx:11403] [ 8] plumed(+0x146dd)[0x5630570f76dd]
[runnervmmklqx:11403] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff36342a1ca]
[runnervmmklqx:11403] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff36342a28b]
[runnervmmklqx:11403] [11] plumed(+0x15365)[0x5630570f8365]
[runnervmmklqx:11403] *** End of error message ***
</pre>
{% endraw %}

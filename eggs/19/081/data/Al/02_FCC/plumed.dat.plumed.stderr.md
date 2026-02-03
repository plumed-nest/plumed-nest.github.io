**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.sMpuNd.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervmkj6or:10232] *** Process received signal ***
[runnervmkj6or:10232] Signal: Aborted (6)
[runnervmkj6or:10232] Signal code:  (-6)
[runnervmkj6or:10232] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23b7045330]
[runnervmkj6or:10232] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23b709eb2c]
[runnervmkj6or:10232] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23b704527e]
[runnervmkj6or:10232] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23b70288ff]
[runnervmkj6or:10232] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23b74a5ff5]
[runnervmkj6or:10232] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23b74bb0da]
[runnervmkj6or:10232] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23b74a5a55]
[runnervmkj6or:10232] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23b74a5a6f]
[runnervmkj6or:10232] [ 8] plumed(+0x146dd)[0x55930bbe26dd]
[runnervmkj6or:10232] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23b702a1ca]
[runnervmkj6or:10232] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23b702a28b]
[runnervmkj6or:10232] [11] plumed(+0x15365)[0x55930bbe3365]
[runnervmkj6or:10232] *** End of error message ***
</pre>
{% endraw %}

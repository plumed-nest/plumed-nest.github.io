**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.4r1SRP.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az797-511:09435] *** Process received signal ***
[fv-az797-511:09435] Signal: Aborted (6)
[fv-az797-511:09435] Signal code:  (-6)
[fv-az797-511:09435] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d79845330]
[fv-az797-511:09435] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d7989eb2c]
[fv-az797-511:09435] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d7984527e]
[fv-az797-511:09435] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d798288ff]
[fv-az797-511:09435] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d79ca5ff5]
[fv-az797-511:09435] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d79cbb0da]
[fv-az797-511:09435] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d79ca5a55]
[fv-az797-511:09435] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d79ca5a6f]
[fv-az797-511:09435] [ 8] plumed(+0x146dd)[0x558d99ce76dd]
[fv-az797-511:09435] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d7982a1ca]
[fv-az797-511:09435] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d7982a28b]
[fv-az797-511:09435] [11] plumed(+0x15365)[0x558d99ce8365]
[fv-az797-511:09435] *** End of error message ***
</pre>
{% endraw %}

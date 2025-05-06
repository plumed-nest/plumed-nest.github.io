**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.rbY0xQ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az807-718:68260] *** Process received signal ***
[fv-az807-718:68260] Signal: Aborted (6)
[fv-az807-718:68260] Signal code:  (-6)
[fv-az807-718:68260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a78e45330]
[fv-az807-718:68260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a78e9eb2c]
[fv-az807-718:68260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a78e4527e]
[fv-az807-718:68260] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a78e288ff]
[fv-az807-718:68260] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a792a5ff5]
[fv-az807-718:68260] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a792bb0da]
[fv-az807-718:68260] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a792a5a55]
[fv-az807-718:68260] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a792a5a6f]
[fv-az807-718:68260] [ 8] plumed(+0x146dd)[0x5615dc2ff6dd]
[fv-az807-718:68260] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a78e2a1ca]
[fv-az807-718:68260] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a78e2a28b]
[fv-az807-718:68260] [11] plumed(+0x15365)[0x5615dc300365]
[fv-az807-718:68260] *** End of error message ***
</pre>
{% endraw %}

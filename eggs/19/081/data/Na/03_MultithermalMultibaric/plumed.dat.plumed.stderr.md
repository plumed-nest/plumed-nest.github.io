**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.PfO7Xf.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmf6wy0o8zjz:41751] *** Process received signal ***
[pkrvmf6wy0o8zjz:41751] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:41751] Signal code:  (-6)
[pkrvmf6wy0o8zjz:41751] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d2de45330]
[pkrvmf6wy0o8zjz:41751] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d2de9eb2c]
[pkrvmf6wy0o8zjz:41751] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d2de4527e]
[pkrvmf6wy0o8zjz:41751] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d2de288ff]
[pkrvmf6wy0o8zjz:41751] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d2e2a5ff5]
[pkrvmf6wy0o8zjz:41751] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d2e2bb0da]
[pkrvmf6wy0o8zjz:41751] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d2e2a5a55]
[pkrvmf6wy0o8zjz:41751] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d2e2a5a6f]
[pkrvmf6wy0o8zjz:41751] [ 8] plumed(+0x146dd)[0x56553fce56dd]
[pkrvmf6wy0o8zjz:41751] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d2de2a1ca]
[pkrvmf6wy0o8zjz:41751] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d2de2a28b]
[pkrvmf6wy0o8zjz:41751] [11] plumed(+0x15365)[0x56553fce6365]
[pkrvmf6wy0o8zjz:41751] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.JWlOUZ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmf6wy0o8zjz:40992] *** Process received signal ***
[pkrvmf6wy0o8zjz:40992] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:40992] Signal code:  (-6)
[pkrvmf6wy0o8zjz:40992] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faaa8c45330]
[pkrvmf6wy0o8zjz:40992] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faaa8c9eb2c]
[pkrvmf6wy0o8zjz:40992] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faaa8c4527e]
[pkrvmf6wy0o8zjz:40992] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faaa8c288ff]
[pkrvmf6wy0o8zjz:40992] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faaa90a5ff5]
[pkrvmf6wy0o8zjz:40992] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faaa90bb0da]
[pkrvmf6wy0o8zjz:40992] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faaa90a5a55]
[pkrvmf6wy0o8zjz:40992] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faaa90a5a6f]
[pkrvmf6wy0o8zjz:40992] [ 8] plumed(+0x146dd)[0x55a4dbf136dd]
[pkrvmf6wy0o8zjz:40992] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faaa8c2a1ca]
[pkrvmf6wy0o8zjz:40992] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faaa8c2a28b]
[pkrvmf6wy0o8zjz:40992] [11] plumed(+0x15365)[0x55a4dbf14365]
[pkrvmf6wy0o8zjz:40992] *** End of error message ***
</pre>
{% endraw %}

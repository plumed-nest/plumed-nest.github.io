**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.HdU007.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[pkrvmf6wy0o8zjz:41541] *** Process received signal ***
[pkrvmf6wy0o8zjz:41541] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:41541] Signal code:  (-6)
[pkrvmf6wy0o8zjz:41541] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcbaa245330]
[pkrvmf6wy0o8zjz:41541] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcbaa29eb2c]
[pkrvmf6wy0o8zjz:41541] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcbaa24527e]
[pkrvmf6wy0o8zjz:41541] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcbaa2288ff]
[pkrvmf6wy0o8zjz:41541] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcbaa6a5ff5]
[pkrvmf6wy0o8zjz:41541] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcbaa6bb0da]
[pkrvmf6wy0o8zjz:41541] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcbaa6a5a55]
[pkrvmf6wy0o8zjz:41541] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcbaa6a5a6f]
[pkrvmf6wy0o8zjz:41541] [ 8] plumed(+0x146dd)[0x55a82d9e16dd]
[pkrvmf6wy0o8zjz:41541] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcbaa22a1ca]
[pkrvmf6wy0o8zjz:41541] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcbaa22a28b]
[pkrvmf6wy0o8zjz:41541] [11] plumed(+0x15365)[0x55a82d9e2365]
[pkrvmf6wy0o8zjz:41541] *** End of error message ***
</pre>
{% endraw %}

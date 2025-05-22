**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Solid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.JvMklN.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[pkrvmf6wy0o8zjz:41418] *** Process received signal ***
[pkrvmf6wy0o8zjz:41418] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:41418] Signal code:  (-6)
[pkrvmf6wy0o8zjz:41418] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc482045330]
[pkrvmf6wy0o8zjz:41418] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc48209eb2c]
[pkrvmf6wy0o8zjz:41418] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc48204527e]
[pkrvmf6wy0o8zjz:41418] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4820288ff]
[pkrvmf6wy0o8zjz:41418] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4824a5ff5]
[pkrvmf6wy0o8zjz:41418] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4824bb0da]
[pkrvmf6wy0o8zjz:41418] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4824a5a55]
[pkrvmf6wy0o8zjz:41418] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4824a5a6f]
[pkrvmf6wy0o8zjz:41418] [ 8] plumed(+0x146dd)[0x5647213b86dd]
[pkrvmf6wy0o8zjz:41418] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc48202a1ca]
[pkrvmf6wy0o8zjz:41418] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc48202a28b]
[pkrvmf6wy0o8zjz:41418] [11] plumed(+0x15365)[0x5647213b9365]
[pkrvmf6wy0o8zjz:41418] *** End of error message ***
</pre>
{% endraw %}

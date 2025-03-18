**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Solid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.jvayDG.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[fv-az790-36:68842] *** Process received signal ***
[fv-az790-36:68842] Signal: Aborted (6)
[fv-az790-36:68842] Signal code:  (-6)
[fv-az790-36:68842] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7993845330]
[fv-az790-36:68842] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f799389eb2c]
[fv-az790-36:68842] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f799384527e]
[fv-az790-36:68842] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79938288ff]
[fv-az790-36:68842] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7993ca5ff5]
[fv-az790-36:68842] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7993cbb0da]
[fv-az790-36:68842] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7993ca5a55]
[fv-az790-36:68842] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7993ca5a6f]
[fv-az790-36:68842] [ 8] plumed(+0x146dd)[0x56360508c6dd]
[fv-az790-36:68842] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f799382a1ca]
[fv-az790-36:68842] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f799382a28b]
[fv-az790-36:68842] [11] plumed(+0x15365)[0x56360508d365]
[fv-az790-36:68842] *** End of error message ***
</pre>
{% endraw %}

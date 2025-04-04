**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.4r9Vom.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[fv-az805-507:10135] *** Process received signal ***
[fv-az805-507:10135] Signal: Aborted (6)
[fv-az805-507:10135] Signal code:  (-6)
[fv-az805-507:10135] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9f3bc45330]
[fv-az805-507:10135] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9f3bc9eb2c]
[fv-az805-507:10135] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9f3bc4527e]
[fv-az805-507:10135] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9f3bc288ff]
[fv-az805-507:10135] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9f3c0a5ff5]
[fv-az805-507:10135] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9f3c0bb0da]
[fv-az805-507:10135] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9f3c0a5a55]
[fv-az805-507:10135] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9f3c0a5a6f]
[fv-az805-507:10135] [ 8] plumed(+0x146dd)[0x56297acd66dd]
[fv-az805-507:10135] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9f3bc2a1ca]
[fv-az805-507:10135] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9f3bc2a28b]
[fv-az805-507:10135] [11] plumed(+0x15365)[0x56297acd7365]
[fv-az805-507:10135] *** End of error message ***
</pre>
{% endraw %}

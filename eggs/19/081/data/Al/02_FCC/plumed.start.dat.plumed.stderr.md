**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.3aHOMb.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az805-507:09666] *** Process received signal ***
[fv-az805-507:09666] Signal: Aborted (6)
[fv-az805-507:09666] Signal code:  (-6)
[fv-az805-507:09666] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0751e45330]
[fv-az805-507:09666] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0751e9eb2c]
[fv-az805-507:09666] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0751e4527e]
[fv-az805-507:09666] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0751e288ff]
[fv-az805-507:09666] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07522a5ff5]
[fv-az805-507:09666] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07522bb0da]
[fv-az805-507:09666] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07522a5a55]
[fv-az805-507:09666] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07522a5a6f]
[fv-az805-507:09666] [ 8] plumed(+0x146dd)[0x564a6edcb6dd]
[fv-az805-507:09666] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0751e2a1ca]
[fv-az805-507:09666] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0751e2a28b]
[fv-az805-507:09666] [11] plumed(+0x15365)[0x564a6edcc365]
[fv-az805-507:09666] *** End of error message ***
</pre>
{% endraw %}

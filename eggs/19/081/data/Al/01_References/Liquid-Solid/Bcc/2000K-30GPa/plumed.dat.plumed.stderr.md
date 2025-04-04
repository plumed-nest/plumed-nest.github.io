**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.E1vr5T.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[fv-az805-507:09232] *** Process received signal ***
[fv-az805-507:09232] Signal: Aborted (6)
[fv-az805-507:09232] Signal code:  (-6)
[fv-az805-507:09232] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb7dc045330]
[fv-az805-507:09232] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb7dc09eb2c]
[fv-az805-507:09232] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb7dc04527e]
[fv-az805-507:09232] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7dc0288ff]
[fv-az805-507:09232] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7dc4a5ff5]
[fv-az805-507:09232] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7dc4bb0da]
[fv-az805-507:09232] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7dc4a5a55]
[fv-az805-507:09232] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7dc4a5a6f]
[fv-az805-507:09232] [ 8] plumed(+0x146dd)[0x5627b35d56dd]
[fv-az805-507:09232] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb7dc02a1ca]
[fv-az805-507:09232] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb7dc02a28b]
[fv-az805-507:09232] [11] plumed(+0x15365)[0x5627b35d6365]
[fv-az805-507:09232] *** End of error message ***
</pre>
{% endraw %}

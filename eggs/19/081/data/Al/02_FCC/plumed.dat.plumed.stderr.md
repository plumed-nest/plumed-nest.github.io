**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.9k8NkD.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az805-507:09578] *** Process received signal ***
[fv-az805-507:09578] Signal: Aborted (6)
[fv-az805-507:09578] Signal code:  (-6)
[fv-az805-507:09578] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f62ff645330]
[fv-az805-507:09578] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f62ff69eb2c]
[fv-az805-507:09578] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f62ff64527e]
[fv-az805-507:09578] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62ff6288ff]
[fv-az805-507:09578] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62ffaa5ff5]
[fv-az805-507:09578] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62ffabb0da]
[fv-az805-507:09578] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62ffaa5a55]
[fv-az805-507:09578] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62ffaa5a6f]
[fv-az805-507:09578] [ 8] plumed(+0x146dd)[0x55a995fe66dd]
[fv-az805-507:09578] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f62ff62a1ca]
[fv-az805-507:09578] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f62ff62a28b]
[fv-az805-507:09578] [11] plumed(+0x15365)[0x55a995fe7365]
[fv-az805-507:09578] *** End of error message ***
</pre>
{% endraw %}

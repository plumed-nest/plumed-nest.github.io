**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.YUsISg.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmpptgkbjq6m:13114] *** Process received signal ***
[pkrvmpptgkbjq6m:13114] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13114] Signal code:  (-6)
[pkrvmpptgkbjq6m:13114] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3202e45330]
[pkrvmpptgkbjq6m:13114] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3202e9eb2c]
[pkrvmpptgkbjq6m:13114] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3202e4527e]
[pkrvmpptgkbjq6m:13114] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3202e288ff]
[pkrvmpptgkbjq6m:13114] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32032a5ff5]
[pkrvmpptgkbjq6m:13114] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32032bb0da]
[pkrvmpptgkbjq6m:13114] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32032a5a55]
[pkrvmpptgkbjq6m:13114] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32032a5a6f]
[pkrvmpptgkbjq6m:13114] [ 8] plumed(+0x146dd)[0x56028a2fe6dd]
[pkrvmpptgkbjq6m:13114] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3202e2a1ca]
[pkrvmpptgkbjq6m:13114] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3202e2a28b]
[pkrvmpptgkbjq6m:13114] [11] plumed(+0x15365)[0x56028a2ff365]
[pkrvmpptgkbjq6m:13114] *** End of error message ***
</pre>
{% endraw %}

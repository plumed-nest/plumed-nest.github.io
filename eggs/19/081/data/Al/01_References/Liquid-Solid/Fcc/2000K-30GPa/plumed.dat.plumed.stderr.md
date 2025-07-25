**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.0mD8MO.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[pkrvmpptgkbjq6m:12944] *** Process received signal ***
[pkrvmpptgkbjq6m:12944] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12944] Signal code:  (-6)
[pkrvmpptgkbjq6m:12944] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3818445330]
[pkrvmpptgkbjq6m:12944] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f381849eb2c]
[pkrvmpptgkbjq6m:12944] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f381844527e]
[pkrvmpptgkbjq6m:12944] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f38184288ff]
[pkrvmpptgkbjq6m:12944] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f38188a5ff5]
[pkrvmpptgkbjq6m:12944] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f38188bb0da]
[pkrvmpptgkbjq6m:12944] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f38188a5a55]
[pkrvmpptgkbjq6m:12944] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f38188a5a6f]
[pkrvmpptgkbjq6m:12944] [ 8] plumed(+0x146dd)[0x55c6508ed6dd]
[pkrvmpptgkbjq6m:12944] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f381842a1ca]
[pkrvmpptgkbjq6m:12944] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f381842a28b]
[pkrvmpptgkbjq6m:12944] [11] plumed(+0x15365)[0x55c6508ee365]
[pkrvmpptgkbjq6m:12944] *** End of error message ***
</pre>
{% endraw %}

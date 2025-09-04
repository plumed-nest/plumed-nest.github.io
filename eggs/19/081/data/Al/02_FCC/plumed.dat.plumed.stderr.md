**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.C6OL7W.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[pkrvm7jw40e0xgp:12792] *** Process received signal ***
[pkrvm7jw40e0xgp:12792] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12792] Signal code:  (-6)
[pkrvm7jw40e0xgp:12792] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5908845330]
[pkrvm7jw40e0xgp:12792] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f590889eb2c]
[pkrvm7jw40e0xgp:12792] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f590884527e]
[pkrvm7jw40e0xgp:12792] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59088288ff]
[pkrvm7jw40e0xgp:12792] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5908ca5ff5]
[pkrvm7jw40e0xgp:12792] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5908cbb0da]
[pkrvm7jw40e0xgp:12792] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5908ca5a55]
[pkrvm7jw40e0xgp:12792] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5908ca5a6f]
[pkrvm7jw40e0xgp:12792] [ 8] plumed(+0x146dd)[0x557c0a0e76dd]
[pkrvm7jw40e0xgp:12792] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f590882a1ca]
[pkrvm7jw40e0xgp:12792] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f590882a28b]
[pkrvm7jw40e0xgp:12792] [11] plumed(+0x15365)[0x557c0a0e8365]
[pkrvm7jw40e0xgp:12792] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.nNI1jA.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[pkrvm7jw40e0xgp:13343] *** Process received signal ***
[pkrvm7jw40e0xgp:13343] Signal: Aborted (6)
[pkrvm7jw40e0xgp:13343] Signal code:  (-6)
[pkrvm7jw40e0xgp:13343] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24bae45330]
[pkrvm7jw40e0xgp:13343] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24bae9eb2c]
[pkrvm7jw40e0xgp:13343] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24bae4527e]
[pkrvm7jw40e0xgp:13343] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24bae288ff]
[pkrvm7jw40e0xgp:13343] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24bb2a5ff5]
[pkrvm7jw40e0xgp:13343] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24bb2bb0da]
[pkrvm7jw40e0xgp:13343] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24bb2a5a55]
[pkrvm7jw40e0xgp:13343] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24bb2a5a6f]
[pkrvm7jw40e0xgp:13343] [ 8] plumed(+0x146dd)[0x55bf47c0f6dd]
[pkrvm7jw40e0xgp:13343] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24bae2a1ca]
[pkrvm7jw40e0xgp:13343] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24bae2a28b]
[pkrvm7jw40e0xgp:13343] [11] plumed(+0x15365)[0x55bf47c10365]
[pkrvm7jw40e0xgp:13343] *** End of error message ***
</pre>
{% endraw %}

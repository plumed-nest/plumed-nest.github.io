**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.syb9Wv.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervmmtnos:38647] *** Process received signal ***
[runnervmmtnos:38647] Signal: Aborted (6)
[runnervmmtnos:38647] Signal code:  (-6)
[runnervmmtnos:38647] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f14f9445330]
[runnervmmtnos:38647] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f14f949eb2c]
[runnervmmtnos:38647] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f14f944527e]
[runnervmmtnos:38647] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f14f94288ff]
[runnervmmtnos:38647] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f14f98a5ff5]
[runnervmmtnos:38647] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f14f98bb0da]
[runnervmmtnos:38647] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f14f98a5a55]
[runnervmmtnos:38647] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f14f98a5a6f]
[runnervmmtnos:38647] [ 8] plumed(+0x146dd)[0x560b4d0f66dd]
[runnervmmtnos:38647] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f14f942a1ca]
[runnervmmtnos:38647] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f14f942a28b]
[runnervmmtnos:38647] [11] plumed(+0x15365)[0x560b4d0f7365]
[runnervmmtnos:38647] *** End of error message ***
</pre>
{% endraw %}

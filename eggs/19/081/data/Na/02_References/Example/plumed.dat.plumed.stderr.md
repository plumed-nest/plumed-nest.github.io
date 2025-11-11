**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.iqHAOF.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervmw9dnm:10509] *** Process received signal ***
[runnervmw9dnm:10509] Signal: Aborted (6)
[runnervmw9dnm:10509] Signal code:  (-6)
[runnervmw9dnm:10509] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb421045330]
[runnervmw9dnm:10509] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb42109eb2c]
[runnervmw9dnm:10509] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb42104527e]
[runnervmw9dnm:10509] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4210288ff]
[runnervmw9dnm:10509] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4214a5ff5]
[runnervmw9dnm:10509] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4214bb0da]
[runnervmw9dnm:10509] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4214a5a55]
[runnervmw9dnm:10509] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4214a5a6f]
[runnervmw9dnm:10509] [ 8] plumed(+0x146dd)[0x556ad901f6dd]
[runnervmw9dnm:10509] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb42102a1ca]
[runnervmw9dnm:10509] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb42102a28b]
[runnervmw9dnm:10509] [11] plumed(+0x15365)[0x556ad9020365]
[runnervmw9dnm:10509] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.kSC0jJ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[runnervmw9dnm:10333] *** Process received signal ***
[runnervmw9dnm:10333] Signal: Aborted (6)
[runnervmw9dnm:10333] Signal code:  (-6)
[runnervmw9dnm:10333] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff7cf445330]
[runnervmw9dnm:10333] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff7cf49eb2c]
[runnervmw9dnm:10333] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff7cf44527e]
[runnervmw9dnm:10333] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff7cf4288ff]
[runnervmw9dnm:10333] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff7cf8a5ff5]
[runnervmw9dnm:10333] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff7cf8bb0da]
[runnervmw9dnm:10333] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff7cf8a5a55]
[runnervmw9dnm:10333] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff7cf8a5a6f]
[runnervmw9dnm:10333] [ 8] plumed_master(+0x146dd)[0x559e9ce9a6dd]
[runnervmw9dnm:10333] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff7cf42a1ca]
[runnervmw9dnm:10333] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff7cf42a28b]
[runnervmw9dnm:10333] [11] plumed_master(+0x15365)[0x559e9ce9b365]
[runnervmw9dnm:10333] *** End of error message ***
</pre>
{% endraw %}

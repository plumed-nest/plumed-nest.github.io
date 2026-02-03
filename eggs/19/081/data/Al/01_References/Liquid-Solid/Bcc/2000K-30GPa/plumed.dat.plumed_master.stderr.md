**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.wTWyE7.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[runnervmkj6or:09921] *** Process received signal ***
[runnervmkj6or:09921] Signal: Aborted (6)
[runnervmkj6or:09921] Signal code:  (-6)
[runnervmkj6or:09921] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff13c645330]
[runnervmkj6or:09921] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff13c69eb2c]
[runnervmkj6or:09921] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff13c64527e]
[runnervmkj6or:09921] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff13c6288ff]
[runnervmkj6or:09921] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff13caa5ff5]
[runnervmkj6or:09921] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff13cabb0da]
[runnervmkj6or:09921] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff13caa5a55]
[runnervmkj6or:09921] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff13caa5a6f]
[runnervmkj6or:09921] [ 8] plumed_master(+0x146dd)[0x55dd692036dd]
[runnervmkj6or:09921] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff13c62a1ca]
[runnervmkj6or:09921] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff13c62a28b]
[runnervmkj6or:09921] [11] plumed_master(+0x15365)[0x55dd69204365]
[runnervmkj6or:09921] *** End of error message ***
</pre>
{% endraw %}

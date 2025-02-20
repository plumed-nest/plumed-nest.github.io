**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.KGoV37.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[fv-az797-511:09469] *** Process received signal ***
[fv-az797-511:09469] Signal: Aborted (6)
[fv-az797-511:09469] Signal code:  (-6)
[fv-az797-511:09469] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc00c845330]
[fv-az797-511:09469] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc00c89eb2c]
[fv-az797-511:09469] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc00c84527e]
[fv-az797-511:09469] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc00c8288ff]
[fv-az797-511:09469] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc00cca5ff5]
[fv-az797-511:09469] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc00ccbb0da]
[fv-az797-511:09469] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc00cca5a55]
[fv-az797-511:09469] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc00cca5a6f]
[fv-az797-511:09469] [ 8] plumed_master(+0x146dd)[0x55d1c1eb06dd]
[fv-az797-511:09469] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc00c82a1ca]
[fv-az797-511:09469] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc00c82a28b]
[fv-az797-511:09469] [11] plumed_master(+0x15365)[0x55d1c1eb1365]
[fv-az797-511:09469] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.KOx7TV.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[fv-az805-507:09350] *** Process received signal ***
[fv-az805-507:09350] Signal: Aborted (6)
[fv-az805-507:09350] Signal code:  (-6)
[fv-az805-507:09350] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4be4e45330]
[fv-az805-507:09350] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4be4e9eb2c]
[fv-az805-507:09350] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4be4e4527e]
[fv-az805-507:09350] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4be4e288ff]
[fv-az805-507:09350] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4be52a5ff5]
[fv-az805-507:09350] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4be52bb0da]
[fv-az805-507:09350] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4be52a5a55]
[fv-az805-507:09350] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4be52a5a6f]
[fv-az805-507:09350] [ 8] plumed_master(+0x146dd)[0x55751677a6dd]
[fv-az805-507:09350] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4be4e2a1ca]
[fv-az805-507:09350] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4be4e2a28b]
[fv-az805-507:09350] [11] plumed_master(+0x15365)[0x55751677b365]
[fv-az805-507:09350] *** End of error message ***
</pre>
{% endraw %}

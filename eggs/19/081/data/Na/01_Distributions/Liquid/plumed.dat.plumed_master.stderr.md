**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.s5fnuy.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[fv-az807-718:67729] *** Process received signal ***
[fv-az807-718:67729] Signal: Aborted (6)
[fv-az807-718:67729] Signal code:  (-6)
[fv-az807-718:67729] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a56245330]
[fv-az807-718:67729] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a5629eb2c]
[fv-az807-718:67729] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a5624527e]
[fv-az807-718:67729] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a562288ff]
[fv-az807-718:67729] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a566a5ff5]
[fv-az807-718:67729] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a566bb0da]
[fv-az807-718:67729] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a566a5a55]
[fv-az807-718:67729] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a566a5a6f]
[fv-az807-718:67729] [ 8] plumed_master(+0x146dd)[0x55c660e086dd]
[fv-az807-718:67729] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a5622a1ca]
[fv-az807-718:67729] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a5622a28b]
[fv-az807-718:67729] [11] plumed_master(+0x15365)[0x55c660e09365]
[fv-az807-718:67729] *** End of error message ***
</pre>
{% endraw %}

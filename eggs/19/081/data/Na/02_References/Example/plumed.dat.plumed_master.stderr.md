**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.5xxgOk.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[pkrvmpptgkbjq6m:13701] *** Process received signal ***
[pkrvmpptgkbjq6m:13701] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13701] Signal code:  (-6)
[pkrvmpptgkbjq6m:13701] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc7f8a45330]
[pkrvmpptgkbjq6m:13701] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc7f8a9eb2c]
[pkrvmpptgkbjq6m:13701] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc7f8a4527e]
[pkrvmpptgkbjq6m:13701] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7f8a288ff]
[pkrvmpptgkbjq6m:13701] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7f8ea5ff5]
[pkrvmpptgkbjq6m:13701] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7f8ebb0da]
[pkrvmpptgkbjq6m:13701] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7f8ea5a55]
[pkrvmpptgkbjq6m:13701] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7f8ea5a6f]
[pkrvmpptgkbjq6m:13701] [ 8] plumed_master(+0x146dd)[0x5626974b06dd]
[pkrvmpptgkbjq6m:13701] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc7f8a2a1ca]
[pkrvmpptgkbjq6m:13701] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc7f8a2a28b]
[pkrvmpptgkbjq6m:13701] [11] plumed_master(+0x15365)[0x5626974b1365]
[pkrvmpptgkbjq6m:13701] *** End of error message ***
</pre>
{% endraw %}

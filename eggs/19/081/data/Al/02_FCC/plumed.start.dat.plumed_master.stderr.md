**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.8XIPUo.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[pkrvmpptgkbjq6m:13232] *** Process received signal ***
[pkrvmpptgkbjq6m:13232] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13232] Signal code:  (-6)
[pkrvmpptgkbjq6m:13232] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf5c645330]
[pkrvmpptgkbjq6m:13232] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf5c69eb2c]
[pkrvmpptgkbjq6m:13232] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf5c64527e]
[pkrvmpptgkbjq6m:13232] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf5c6288ff]
[pkrvmpptgkbjq6m:13232] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf5caa5ff5]
[pkrvmpptgkbjq6m:13232] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf5cabb0da]
[pkrvmpptgkbjq6m:13232] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf5caa5a55]
[pkrvmpptgkbjq6m:13232] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf5caa5a6f]
[pkrvmpptgkbjq6m:13232] [ 8] plumed_master(+0x146dd)[0x5638b71176dd]
[pkrvmpptgkbjq6m:13232] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf5c62a1ca]
[pkrvmpptgkbjq6m:13232] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf5c62a28b]
[pkrvmpptgkbjq6m:13232] [11] plumed_master(+0x15365)[0x5638b7118365]
[pkrvmpptgkbjq6m:13232] *** End of error message ***
</pre>
{% endraw %}

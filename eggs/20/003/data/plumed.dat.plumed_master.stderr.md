**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.qaQJTD.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1260) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT="/home/runner/opt/lib/plumed_master" env PLUMED_VERSION="2.10.0-dev" env PLUMED_HTMLDIR="/home/runner/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/runner/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh TD_TS-target-plumed2.6.cpp

[fv-az1108-992:72805] *** Process received signal ***
[fv-az1108-992:72805] Signal: Aborted (6)
[fv-az1108-992:72805] Signal code:  (-6)
[fv-az1108-992:72805] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8a2a842520]
[fv-az1108-992:72805] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8a2a8969fc]
[fv-az1108-992:72805] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8a2a842476]
[fv-az1108-992:72805] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8a2a8287f3]
[fv-az1108-992:72805] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f8a2aca4f26]
[fv-az1108-992:72805] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f8a2acb6d9c]
[fv-az1108-992:72805] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f8a2acb6e07]
[fv-az1108-992:72805] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8a2acb70bb]
[fv-az1108-992:72805] [ 8] plumed_master(+0x12e7f)[0x564431f50e7f]
[fv-az1108-992:72805] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8a2a829d90]
[fv-az1108-992:72805] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8a2a829e40]
[fv-az1108-992:72805] [11] plumed_master(+0x13115)[0x564431f51115]
[fv-az1108-992:72805] *** End of error message ***
</pre>
{% endraw %}

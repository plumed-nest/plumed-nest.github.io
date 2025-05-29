**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.k1l4bb.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.10b.so TD_TS-target-plumed2.6.cpp

[pkrvmf6wy0o8zjz:67539] *** Process received signal ***
[pkrvmf6wy0o8zjz:67539] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:67539] Signal code:  (-6)
[pkrvmf6wy0o8zjz:67539] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2452245330]
[pkrvmf6wy0o8zjz:67539] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f245229eb2c]
[pkrvmf6wy0o8zjz:67539] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f245224527e]
[pkrvmf6wy0o8zjz:67539] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24522288ff]
[pkrvmf6wy0o8zjz:67539] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24526a5ff5]
[pkrvmf6wy0o8zjz:67539] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24526bb0da]
[pkrvmf6wy0o8zjz:67539] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24526a5a55]
[pkrvmf6wy0o8zjz:67539] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24526a5a6f]
[pkrvmf6wy0o8zjz:67539] [ 8] plumed(+0x146dd)[0x56514e9e86dd]
[pkrvmf6wy0o8zjz:67539] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f245222a1ca]
[pkrvmf6wy0o8zjz:67539] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f245222a28b]
[pkrvmf6wy0o8zjz:67539] [11] plumed(+0x15365)[0x56514e9e9365]
[pkrvmf6wy0o8zjz:67539] *** End of error message ***
</pre>
{% endraw %}

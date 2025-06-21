**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[pkrvmxyh4eaekms:06334] *** Process received signal ***
[pkrvmxyh4eaekms:06334] Signal: Aborted (6)
[pkrvmxyh4eaekms:06334] Signal code:  (-6)
[pkrvmxyh4eaekms:06334] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4357a45330]
[pkrvmxyh4eaekms:06334] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4357a9eb2c]
[pkrvmxyh4eaekms:06334] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4357a4527e]
[pkrvmxyh4eaekms:06334] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4357a288ff]
[pkrvmxyh4eaekms:06334] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4357ea5ff5]
[pkrvmxyh4eaekms:06334] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4357ebb0da]
[pkrvmxyh4eaekms:06334] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4357ea5a55]
[pkrvmxyh4eaekms:06334] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4357ea5a6f]
[pkrvmxyh4eaekms:06334] [ 8] plumed(+0x146dd)[0x560f43c8b6dd]
[pkrvmxyh4eaekms:06334] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4357a2a1ca]
[pkrvmxyh4eaekms:06334] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4357a2a28b]
[pkrvmxyh4eaekms:06334] [11] plumed(+0x15365)[0x560f43c8c365]
[pkrvmxyh4eaekms:06334] *** End of error message ***
</pre>
{% endraw %}

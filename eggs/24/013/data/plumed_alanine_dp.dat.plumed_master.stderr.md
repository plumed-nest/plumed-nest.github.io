**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[pkrvmxyh4eaekms:06349] *** Process received signal ***
[pkrvmxyh4eaekms:06349] Signal: Aborted (6)
[pkrvmxyh4eaekms:06349] Signal code:  (-6)
[pkrvmxyh4eaekms:06349] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd534c45330]
[pkrvmxyh4eaekms:06349] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd534c9eb2c]
[pkrvmxyh4eaekms:06349] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd534c4527e]
[pkrvmxyh4eaekms:06349] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd534c288ff]
[pkrvmxyh4eaekms:06349] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd5350a5ff5]
[pkrvmxyh4eaekms:06349] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd5350bb0da]
[pkrvmxyh4eaekms:06349] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd5350a5a55]
[pkrvmxyh4eaekms:06349] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd5350a5a6f]
[pkrvmxyh4eaekms:06349] [ 8] plumed_master(+0x146dd)[0x55f2dd4e96dd]
[pkrvmxyh4eaekms:06349] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd534c2a1ca]
[pkrvmxyh4eaekms:06349] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd534c2a28b]
[pkrvmxyh4eaekms:06349] [11] plumed_master(+0x15365)[0x55f2dd4ea365]
[pkrvmxyh4eaekms:06349] *** End of error message ***
</pre>
{% endraw %}

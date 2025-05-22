**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[pkrvmf6wy0o8zjz:35812] *** Process received signal ***
[pkrvmf6wy0o8zjz:35812] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:35812] Signal code:  (-6)
[pkrvmf6wy0o8zjz:35812] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe1d9445330]
[pkrvmf6wy0o8zjz:35812] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe1d949eb2c]
[pkrvmf6wy0o8zjz:35812] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe1d944527e]
[pkrvmf6wy0o8zjz:35812] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe1d94288ff]
[pkrvmf6wy0o8zjz:35812] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe1d98a5ff5]
[pkrvmf6wy0o8zjz:35812] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe1d98bb0da]
[pkrvmf6wy0o8zjz:35812] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe1d98a5a55]
[pkrvmf6wy0o8zjz:35812] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe1d98a5a6f]
[pkrvmf6wy0o8zjz:35812] [ 8] plumed_master(+0x146dd)[0x5556741286dd]
[pkrvmf6wy0o8zjz:35812] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe1d942a1ca]
[pkrvmf6wy0o8zjz:35812] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe1d942a28b]
[pkrvmf6wy0o8zjz:35812] [11] plumed_master(+0x15365)[0x555674129365]
[pkrvmf6wy0o8zjz:35812] *** End of error message ***
</pre>
{% endraw %}

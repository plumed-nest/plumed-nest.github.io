**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[pkrvmf6wy0o8zjz:69252] *** Process received signal ***
[pkrvmf6wy0o8zjz:69252] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69252] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69252] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd236845330]
[pkrvmf6wy0o8zjz:69252] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd23689eb2c]
[pkrvmf6wy0o8zjz:69252] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd23684527e]
[pkrvmf6wy0o8zjz:69252] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2368288ff]
[pkrvmf6wy0o8zjz:69252] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd236ca5ff5]
[pkrvmf6wy0o8zjz:69252] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd236cbb0da]
[pkrvmf6wy0o8zjz:69252] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd236ca5a55]
[pkrvmf6wy0o8zjz:69252] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd236ca5a6f]
[pkrvmf6wy0o8zjz:69252] [ 8] plumed_master(+0x146dd)[0x55f6066376dd]
[pkrvmf6wy0o8zjz:69252] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd23682a1ca]
[pkrvmf6wy0o8zjz:69252] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd23682a28b]
[pkrvmf6wy0o8zjz:69252] [11] plumed_master(+0x15365)[0x55f606638365]
[pkrvmf6wy0o8zjz:69252] *** End of error message ***
</pre>
{% endraw %}

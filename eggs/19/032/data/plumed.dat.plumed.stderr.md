**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[pkrvmf6wy0o8zjz:40650] *** Process received signal ***
[pkrvmf6wy0o8zjz:40650] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:40650] Signal code:  (-6)
[pkrvmf6wy0o8zjz:40650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e8c045330]
[pkrvmf6wy0o8zjz:40650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e8c09eb2c]
[pkrvmf6wy0o8zjz:40650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e8c04527e]
[pkrvmf6wy0o8zjz:40650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e8c0288ff]
[pkrvmf6wy0o8zjz:40650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e8c4a5ff5]
[pkrvmf6wy0o8zjz:40650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e8c4bb0da]
[pkrvmf6wy0o8zjz:40650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e8c4a5a55]
[pkrvmf6wy0o8zjz:40650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e8c4a5a6f]
[pkrvmf6wy0o8zjz:40650] [ 8] plumed(+0x146dd)[0x563f73c8b6dd]
[pkrvmf6wy0o8zjz:40650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e8c02a1ca]
[pkrvmf6wy0o8zjz:40650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e8c02a28b]
[pkrvmf6wy0o8zjz:40650] [11] plumed(+0x15365)[0x563f73c8c365]
[pkrvmf6wy0o8zjz:40650] *** End of error message ***
</pre>
{% endraw %}

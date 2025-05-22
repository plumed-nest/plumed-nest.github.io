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
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[pkrvmf6wy0o8zjz:40666] *** Process received signal ***
[pkrvmf6wy0o8zjz:40666] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:40666] Signal code:  (-6)
[pkrvmf6wy0o8zjz:40666] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d61645330]
[pkrvmf6wy0o8zjz:40666] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d6169eb2c]
[pkrvmf6wy0o8zjz:40666] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d6164527e]
[pkrvmf6wy0o8zjz:40666] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d616288ff]
[pkrvmf6wy0o8zjz:40666] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d61aa5ff5]
[pkrvmf6wy0o8zjz:40666] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d61abb0da]
[pkrvmf6wy0o8zjz:40666] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d61aa5a55]
[pkrvmf6wy0o8zjz:40666] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d61aa5a6f]
[pkrvmf6wy0o8zjz:40666] [ 8] plumed_master(+0x146dd)[0x564644ec46dd]
[pkrvmf6wy0o8zjz:40666] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d6162a1ca]
[pkrvmf6wy0o8zjz:40666] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d6162a28b]
[pkrvmf6wy0o8zjz:40666] [11] plumed_master(+0x15365)[0x564644ec5365]
[pkrvmf6wy0o8zjz:40666] *** End of error message ***
</pre>
{% endraw %}

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
[pkrvmf6wy0o8zjz:69236] *** Process received signal ***
[pkrvmf6wy0o8zjz:69236] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69236] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69236] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7abaa45330]
[pkrvmf6wy0o8zjz:69236] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7abaa9eb2c]
[pkrvmf6wy0o8zjz:69236] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7abaa4527e]
[pkrvmf6wy0o8zjz:69236] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7abaa288ff]
[pkrvmf6wy0o8zjz:69236] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7abaea5ff5]
[pkrvmf6wy0o8zjz:69236] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7abaebb0da]
[pkrvmf6wy0o8zjz:69236] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7abaea5a55]
[pkrvmf6wy0o8zjz:69236] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7abaea5a6f]
[pkrvmf6wy0o8zjz:69236] [ 8] plumed(+0x146dd)[0x55c19100d6dd]
[pkrvmf6wy0o8zjz:69236] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7abaa2a1ca]
[pkrvmf6wy0o8zjz:69236] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7abaa2a28b]
[pkrvmf6wy0o8zjz:69236] [11] plumed(+0x15365)[0x55c19100e365]
[pkrvmf6wy0o8zjz:69236] *** End of error message ***
</pre>
{% endraw %}

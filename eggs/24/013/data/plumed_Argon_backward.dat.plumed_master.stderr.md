**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmf6wy0o8zjz:34864] *** Process received signal ***
[pkrvmf6wy0o8zjz:34864] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:34864] Signal code:  (-6)
[pkrvmf6wy0o8zjz:34864] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a7b245330]
[pkrvmf6wy0o8zjz:34864] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a7b29eb2c]
[pkrvmf6wy0o8zjz:34864] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a7b24527e]
[pkrvmf6wy0o8zjz:34864] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a7b2288ff]
[pkrvmf6wy0o8zjz:34864] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a7b6a5ff5]
[pkrvmf6wy0o8zjz:34864] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a7b6bb0da]
[pkrvmf6wy0o8zjz:34864] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a7b6a5a55]
[pkrvmf6wy0o8zjz:34864] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a7b6a5a6f]
[pkrvmf6wy0o8zjz:34864] [ 8] plumed_master(+0x146dd)[0x561eccd3e6dd]
[pkrvmf6wy0o8zjz:34864] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a7b22a1ca]
[pkrvmf6wy0o8zjz:34864] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a7b22a28b]
[pkrvmf6wy0o8zjz:34864] [11] plumed_master(+0x15365)[0x561eccd3f365]
[pkrvmf6wy0o8zjz:34864] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:40023] *** Process received signal ***
[pkrvmf6wy0o8zjz:40023] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:40023] Signal code:  (-6)
[pkrvmf6wy0o8zjz:40023] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d36445330]
[pkrvmf6wy0o8zjz:40023] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d3649eb2c]
[pkrvmf6wy0o8zjz:40023] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d3644527e]
[pkrvmf6wy0o8zjz:40023] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d364288ff]
[pkrvmf6wy0o8zjz:40023] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d368a5ff5]
[pkrvmf6wy0o8zjz:40023] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d368bb0da]
[pkrvmf6wy0o8zjz:40023] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d368a5a55]
[pkrvmf6wy0o8zjz:40023] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d368a5a6f]
[pkrvmf6wy0o8zjz:40023] [ 8] plumed_master(+0x146dd)[0x56267c1576dd]
[pkrvmf6wy0o8zjz:40023] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d3642a1ca]
[pkrvmf6wy0o8zjz:40023] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d3642a28b]
[pkrvmf6wy0o8zjz:40023] [11] plumed_master(+0x15365)[0x56267c158365]
[pkrvmf6wy0o8zjz:40023] *** End of error message ***
</pre>
{% endraw %}

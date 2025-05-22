**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:40380] *** Process received signal ***
[pkrvmf6wy0o8zjz:40380] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:40380] Signal code:  (-6)
[pkrvmf6wy0o8zjz:40380] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd22dc45330]
[pkrvmf6wy0o8zjz:40380] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd22dc9eb2c]
[pkrvmf6wy0o8zjz:40380] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd22dc4527e]
[pkrvmf6wy0o8zjz:40380] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd22dc288ff]
[pkrvmf6wy0o8zjz:40380] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd22e0a5ff5]
[pkrvmf6wy0o8zjz:40380] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd22e0bb0da]
[pkrvmf6wy0o8zjz:40380] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd22e0a5a55]
[pkrvmf6wy0o8zjz:40380] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd22e0a5a6f]
[pkrvmf6wy0o8zjz:40380] [ 8] plumed_master(+0x146dd)[0x55bd5c54d6dd]
[pkrvmf6wy0o8zjz:40380] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd22dc2a1ca]
[pkrvmf6wy0o8zjz:40380] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd22dc2a28b]
[pkrvmf6wy0o8zjz:40380] [11] plumed_master(+0x15365)[0x55bd5c54e365]
[pkrvmf6wy0o8zjz:40380] *** End of error message ***
</pre>
{% endraw %}

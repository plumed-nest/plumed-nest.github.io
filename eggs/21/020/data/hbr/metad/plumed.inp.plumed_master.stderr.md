**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @51 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:66566] *** Process received signal ***
[pkrvmf6wy0o8zjz:66566] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:66566] Signal code:  (-6)
[pkrvmf6wy0o8zjz:66566] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b1a045330]
[pkrvmf6wy0o8zjz:66566] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b1a09eb2c]
[pkrvmf6wy0o8zjz:66566] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b1a04527e]
[pkrvmf6wy0o8zjz:66566] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b1a0288ff]
[pkrvmf6wy0o8zjz:66566] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b1a4a5ff5]
[pkrvmf6wy0o8zjz:66566] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b1a4bb0da]
[pkrvmf6wy0o8zjz:66566] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b1a4a5a55]
[pkrvmf6wy0o8zjz:66566] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b1a4a5a6f]
[pkrvmf6wy0o8zjz:66566] [ 8] plumed_master(+0x146dd)[0x55c8479ea6dd]
[pkrvmf6wy0o8zjz:66566] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b1a02a1ca]
[pkrvmf6wy0o8zjz:66566] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b1a02a28b]
[pkrvmf6wy0o8zjz:66566] [11] plumed_master(+0x15365)[0x55c8479eb365]
[pkrvmf6wy0o8zjz:66566] *** End of error message ***
</pre>
{% endraw %}

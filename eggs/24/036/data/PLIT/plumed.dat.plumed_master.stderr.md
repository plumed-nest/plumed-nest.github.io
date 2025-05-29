**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:61826] *** Process received signal ***
[pkrvmf6wy0o8zjz:61826] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:61826] Signal code:  (-6)
[pkrvmf6wy0o8zjz:61826] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd216445330]
[pkrvmf6wy0o8zjz:61826] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd21649eb2c]
[pkrvmf6wy0o8zjz:61826] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd21644527e]
[pkrvmf6wy0o8zjz:61826] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2164288ff]
[pkrvmf6wy0o8zjz:61826] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2168a5ff5]
[pkrvmf6wy0o8zjz:61826] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2168bb0da]
[pkrvmf6wy0o8zjz:61826] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2168a5a55]
[pkrvmf6wy0o8zjz:61826] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2168a5a6f]
[pkrvmf6wy0o8zjz:61826] [ 8] plumed_master(+0x146dd)[0x55be2016c6dd]
[pkrvmf6wy0o8zjz:61826] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd21642a1ca]
[pkrvmf6wy0o8zjz:61826] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd21642a28b]
[pkrvmf6wy0o8zjz:61826] [11] plumed_master(+0x15365)[0x55be2016d365]
[pkrvmf6wy0o8zjz:61826] *** End of error message ***
</pre>
{% endraw %}

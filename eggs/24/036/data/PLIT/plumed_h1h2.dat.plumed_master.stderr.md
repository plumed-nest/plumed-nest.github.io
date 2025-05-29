**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:61864] *** Process received signal ***
[pkrvmf6wy0o8zjz:61864] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:61864] Signal code:  (-6)
[pkrvmf6wy0o8zjz:61864] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc68f045330]
[pkrvmf6wy0o8zjz:61864] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc68f09eb2c]
[pkrvmf6wy0o8zjz:61864] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc68f04527e]
[pkrvmf6wy0o8zjz:61864] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc68f0288ff]
[pkrvmf6wy0o8zjz:61864] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc68f4a5ff5]
[pkrvmf6wy0o8zjz:61864] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc68f4bb0da]
[pkrvmf6wy0o8zjz:61864] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc68f4a5a55]
[pkrvmf6wy0o8zjz:61864] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc68f4a5a6f]
[pkrvmf6wy0o8zjz:61864] [ 8] plumed_master(+0x146dd)[0x55a6706836dd]
[pkrvmf6wy0o8zjz:61864] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc68f02a1ca]
[pkrvmf6wy0o8zjz:61864] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc68f02a28b]
[pkrvmf6wy0o8zjz:61864] [11] plumed_master(+0x15365)[0x55a670684365]
[pkrvmf6wy0o8zjz:61864] *** End of error message ***
</pre>
{% endraw %}

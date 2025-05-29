**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmf6wy0o8zjz:62278] *** Process received signal ***
[pkrvmf6wy0o8zjz:62278] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62278] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62278] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0328445330]
[pkrvmf6wy0o8zjz:62278] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f032849eb2c]
[pkrvmf6wy0o8zjz:62278] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f032844527e]
[pkrvmf6wy0o8zjz:62278] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03284288ff]
[pkrvmf6wy0o8zjz:62278] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03288a5ff5]
[pkrvmf6wy0o8zjz:62278] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03288bb0da]
[pkrvmf6wy0o8zjz:62278] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03288a5a55]
[pkrvmf6wy0o8zjz:62278] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03288a5a6f]
[pkrvmf6wy0o8zjz:62278] [ 8] plumed_master(+0x146dd)[0x558c620c36dd]
[pkrvmf6wy0o8zjz:62278] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f032842a1ca]
[pkrvmf6wy0o8zjz:62278] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f032842a28b]
[pkrvmf6wy0o8zjz:62278] [11] plumed_master(+0x15365)[0x558c620c4365]
[pkrvmf6wy0o8zjz:62278] *** End of error message ***
</pre>
{% endraw %}

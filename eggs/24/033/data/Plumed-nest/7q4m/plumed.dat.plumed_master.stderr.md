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
[pkrvmf6wy0o8zjz:33380] *** Process received signal ***
[pkrvmf6wy0o8zjz:33380] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:33380] Signal code:  (-6)
[pkrvmf6wy0o8zjz:33380] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f59f3e45330]
[pkrvmf6wy0o8zjz:33380] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f59f3e9eb2c]
[pkrvmf6wy0o8zjz:33380] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f59f3e4527e]
[pkrvmf6wy0o8zjz:33380] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59f3e288ff]
[pkrvmf6wy0o8zjz:33380] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f59f42a5ff5]
[pkrvmf6wy0o8zjz:33380] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f59f42bb0da]
[pkrvmf6wy0o8zjz:33380] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f59f42a5a55]
[pkrvmf6wy0o8zjz:33380] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f59f42a5a6f]
[pkrvmf6wy0o8zjz:33380] [ 8] plumed_master(+0x146dd)[0x557788aef6dd]
[pkrvmf6wy0o8zjz:33380] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f59f3e2a1ca]
[pkrvmf6wy0o8zjz:33380] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f59f3e2a28b]
[pkrvmf6wy0o8zjz:33380] [11] plumed_master(+0x15365)[0x557788af0365]
[pkrvmf6wy0o8zjz:33380] *** End of error message ***
</pre>
{% endraw %}

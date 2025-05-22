**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmf6wy0o8zjz:33206] *** Process received signal ***
[pkrvmf6wy0o8zjz:33206] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:33206] Signal code:  (-6)
[pkrvmf6wy0o8zjz:33206] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff45bc45330]
[pkrvmf6wy0o8zjz:33206] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff45bc9eb2c]
[pkrvmf6wy0o8zjz:33206] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff45bc4527e]
[pkrvmf6wy0o8zjz:33206] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff45bc288ff]
[pkrvmf6wy0o8zjz:33206] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff45c0a5ff5]
[pkrvmf6wy0o8zjz:33206] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff45c0bb0da]
[pkrvmf6wy0o8zjz:33206] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff45c0a5a55]
[pkrvmf6wy0o8zjz:33206] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff45c0a5a6f]
[pkrvmf6wy0o8zjz:33206] [ 8] plumed(+0x146dd)[0x5587d7f8e6dd]
[pkrvmf6wy0o8zjz:33206] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff45bc2a1ca]
[pkrvmf6wy0o8zjz:33206] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff45bc2a28b]
[pkrvmf6wy0o8zjz:33206] [11] plumed(+0x15365)[0x5587d7f8f365]
[pkrvmf6wy0o8zjz:33206] *** End of error message ***
</pre>
{% endraw %}

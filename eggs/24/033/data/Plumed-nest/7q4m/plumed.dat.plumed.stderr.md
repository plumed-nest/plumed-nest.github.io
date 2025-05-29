**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmf6wy0o8zjz:62261] *** Process received signal ***
[pkrvmf6wy0o8zjz:62261] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62261] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62261] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d80045330]
[pkrvmf6wy0o8zjz:62261] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d8009eb2c]
[pkrvmf6wy0o8zjz:62261] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d8004527e]
[pkrvmf6wy0o8zjz:62261] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d800288ff]
[pkrvmf6wy0o8zjz:62261] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d804a5ff5]
[pkrvmf6wy0o8zjz:62261] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d804bb0da]
[pkrvmf6wy0o8zjz:62261] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d804a5a55]
[pkrvmf6wy0o8zjz:62261] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d804a5a6f]
[pkrvmf6wy0o8zjz:62261] [ 8] plumed(+0x146dd)[0x55ca101406dd]
[pkrvmf6wy0o8zjz:62261] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d8002a1ca]
[pkrvmf6wy0o8zjz:62261] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d8002a28b]
[pkrvmf6wy0o8zjz:62261] [11] plumed(+0x15365)[0x55ca10141365]
[pkrvmf6wy0o8zjz:62261] *** End of error message ***
</pre>
{% endraw %}

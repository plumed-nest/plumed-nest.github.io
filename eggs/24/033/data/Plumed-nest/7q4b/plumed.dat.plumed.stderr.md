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
[pkrvmf6wy0o8zjz:62111] *** Process received signal ***
[pkrvmf6wy0o8zjz:62111] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62111] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62111] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f74d2645330]
[pkrvmf6wy0o8zjz:62111] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f74d269eb2c]
[pkrvmf6wy0o8zjz:62111] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f74d264527e]
[pkrvmf6wy0o8zjz:62111] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f74d26288ff]
[pkrvmf6wy0o8zjz:62111] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f74d2aa5ff5]
[pkrvmf6wy0o8zjz:62111] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f74d2abb0da]
[pkrvmf6wy0o8zjz:62111] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f74d2aa5a55]
[pkrvmf6wy0o8zjz:62111] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f74d2aa5a6f]
[pkrvmf6wy0o8zjz:62111] [ 8] plumed(+0x146dd)[0x5631e9b2c6dd]
[pkrvmf6wy0o8zjz:62111] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f74d262a1ca]
[pkrvmf6wy0o8zjz:62111] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f74d262a28b]
[pkrvmf6wy0o8zjz:62111] [11] plumed(+0x15365)[0x5631e9b2d365]
[pkrvmf6wy0o8zjz:62111] *** End of error message ***
</pre>
{% endraw %}

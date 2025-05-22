**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[pkrvmf6wy0o8zjz:37183] *** Process received signal ***
[pkrvmf6wy0o8zjz:37183] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37183] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37183] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa64aa45330]
[pkrvmf6wy0o8zjz:37183] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa64aa9eb2c]
[pkrvmf6wy0o8zjz:37183] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa64aa4527e]
[pkrvmf6wy0o8zjz:37183] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa64aa288ff]
[pkrvmf6wy0o8zjz:37183] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa64aea5ff5]
[pkrvmf6wy0o8zjz:37183] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa64aebb0da]
[pkrvmf6wy0o8zjz:37183] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa64aea5a55]
[pkrvmf6wy0o8zjz:37183] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa64aea5a6f]
[pkrvmf6wy0o8zjz:37183] [ 8] plumed(+0x146dd)[0x55d8acc016dd]
[pkrvmf6wy0o8zjz:37183] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa64aa2a1ca]
[pkrvmf6wy0o8zjz:37183] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa64aa2a28b]
[pkrvmf6wy0o8zjz:37183] [11] plumed(+0x15365)[0x55d8acc02365]
[pkrvmf6wy0o8zjz:37183] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s29 : cannot understand the following words from the input line : LOWMEM
[pkrvmf6wy0o8zjz:63771] *** Process received signal ***
[pkrvmf6wy0o8zjz:63771] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:63771] Signal code:  (-6)
[pkrvmf6wy0o8zjz:63771] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f78b9045330]
[pkrvmf6wy0o8zjz:63771] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f78b909eb2c]
[pkrvmf6wy0o8zjz:63771] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f78b904527e]
[pkrvmf6wy0o8zjz:63771] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f78b90288ff]
[pkrvmf6wy0o8zjz:63771] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f78b94a5ff5]
[pkrvmf6wy0o8zjz:63771] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f78b94bb0da]
[pkrvmf6wy0o8zjz:63771] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f78b94a5a55]
[pkrvmf6wy0o8zjz:63771] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f78b94a5a6f]
[pkrvmf6wy0o8zjz:63771] [ 8] plumed_master(+0x146dd)[0x563005fce6dd]
[pkrvmf6wy0o8zjz:63771] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f78b902a1ca]
[pkrvmf6wy0o8zjz:63771] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f78b902a28b]
[pkrvmf6wy0o8zjz:63771] [11] plumed_master(+0x15365)[0x563005fcf365]
[pkrvmf6wy0o8zjz:63771] *** End of error message ***
</pre>
{% endraw %}

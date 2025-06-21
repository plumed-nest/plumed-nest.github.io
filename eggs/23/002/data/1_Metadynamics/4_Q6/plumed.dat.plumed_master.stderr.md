**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s29 : cannot understand the following words from the input line : LOWMEM
[pkrvmxyh4eaekms:08317] *** Process received signal ***
[pkrvmxyh4eaekms:08317] Signal: Aborted (6)
[pkrvmxyh4eaekms:08317] Signal code:  (-6)
[pkrvmxyh4eaekms:08317] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f881de45330]
[pkrvmxyh4eaekms:08317] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f881de9eb2c]
[pkrvmxyh4eaekms:08317] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f881de4527e]
[pkrvmxyh4eaekms:08317] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f881de288ff]
[pkrvmxyh4eaekms:08317] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f881e2a5ff5]
[pkrvmxyh4eaekms:08317] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f881e2bb0da]
[pkrvmxyh4eaekms:08317] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f881e2a5a55]
[pkrvmxyh4eaekms:08317] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f881e2a5a6f]
[pkrvmxyh4eaekms:08317] [ 8] plumed_master(+0x146dd)[0x55d5a64b06dd]
[pkrvmxyh4eaekms:08317] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f881de2a1ca]
[pkrvmxyh4eaekms:08317] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f881de2a28b]
[pkrvmxyh4eaekms:08317] [11] plumed_master(+0x15365)[0x55d5a64b1365]
[pkrvmxyh4eaekms:08317] *** End of error message ***
</pre>
{% endraw %}

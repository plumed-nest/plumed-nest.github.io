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
[pkrvmxyh4eaekms:08301] *** Process received signal ***
[pkrvmxyh4eaekms:08301] Signal: Aborted (6)
[pkrvmxyh4eaekms:08301] Signal code:  (-6)
[pkrvmxyh4eaekms:08301] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7949a45330]
[pkrvmxyh4eaekms:08301] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7949a9eb2c]
[pkrvmxyh4eaekms:08301] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7949a4527e]
[pkrvmxyh4eaekms:08301] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7949a288ff]
[pkrvmxyh4eaekms:08301] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7949ea5ff5]
[pkrvmxyh4eaekms:08301] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7949ebb0da]
[pkrvmxyh4eaekms:08301] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7949ea5a55]
[pkrvmxyh4eaekms:08301] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7949ea5a6f]
[pkrvmxyh4eaekms:08301] [ 8] plumed(+0x146dd)[0x55f6c571d6dd]
[pkrvmxyh4eaekms:08301] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7949a2a1ca]
[pkrvmxyh4eaekms:08301] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7949a2a28b]
[pkrvmxyh4eaekms:08301] [11] plumed(+0x15365)[0x55f6c571e365]
[pkrvmxyh4eaekms:08301] *** End of error message ***
</pre>
{% endraw %}

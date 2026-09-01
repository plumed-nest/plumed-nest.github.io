**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[runnervmgx7h7:05754] *** Process received signal ***
[runnervmgx7h7:05754] Signal: Aborted (6)
[runnervmgx7h7:05754] Signal code:  (-6)
[runnervmgx7h7:05754] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3a66645330]
[runnervmgx7h7:05754] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3a6669ec0c]
[runnervmgx7h7:05754] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3a6664527e]
[runnervmgx7h7:05754] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3a666288ff]
[runnervmgx7h7:05754] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3a66aa5ff5]
[runnervmgx7h7:05754] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3a66abb0da]
[runnervmgx7h7:05754] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3a66aa5a55]
[runnervmgx7h7:05754] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3a66aa5a6f]
[runnervmgx7h7:05754] [ 8] plumed(+0x146dd)[0x560e5958a6dd]
[runnervmgx7h7:05754] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3a6662a1ca]
[runnervmgx7h7:05754] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3a6662a28b]
[runnervmgx7h7:05754] [11] plumed(+0x15365)[0x560e5958b365]
[runnervmgx7h7:05754] *** End of error message ***
</pre>
{% endraw %}

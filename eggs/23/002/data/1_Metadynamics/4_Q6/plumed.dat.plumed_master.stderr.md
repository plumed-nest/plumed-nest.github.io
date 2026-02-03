**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s29 : cannot understand the following words from the input line : LOWMEM
[runnervmkj6or:06525] *** Process received signal ***
[runnervmkj6or:06525] Signal: Aborted (6)
[runnervmkj6or:06525] Signal code:  (-6)
[runnervmkj6or:06525] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd6c4845330]
[runnervmkj6or:06525] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd6c489eb2c]
[runnervmkj6or:06525] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd6c484527e]
[runnervmkj6or:06525] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6c48288ff]
[runnervmkj6or:06525] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6c4ca5ff5]
[runnervmkj6or:06525] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6c4cbb0da]
[runnervmkj6or:06525] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6c4ca5a55]
[runnervmkj6or:06525] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6c4ca5a6f]
[runnervmkj6or:06525] [ 8] plumed_master(+0x146dd)[0x55d0d6e566dd]
[runnervmkj6or:06525] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd6c482a1ca]
[runnervmkj6or:06525] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd6c482a28b]
[runnervmkj6or:06525] [11] plumed_master(+0x15365)[0x55d0d6e57365]
[runnervmkj6or:06525] *** End of error message ***
</pre>
{% endraw %}

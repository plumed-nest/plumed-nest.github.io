**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s29 : cannot understand the following words from the input line : LOWMEM
[runnervmmklqx:06537] *** Process received signal ***
[runnervmmklqx:06537] Signal: Aborted (6)
[runnervmmklqx:06537] Signal code:  (-6)
[runnervmmklqx:06537] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f69f4845330]
[runnervmmklqx:06537] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f69f489eb2c]
[runnervmmklqx:06537] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f69f484527e]
[runnervmmklqx:06537] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f69f48288ff]
[runnervmmklqx:06537] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f69f4ca5ff5]
[runnervmmklqx:06537] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f69f4cbb0da]
[runnervmmklqx:06537] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f69f4ca5a55]
[runnervmmklqx:06537] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f69f4ca5a6f]
[runnervmmklqx:06537] [ 8] plumed_master(+0x146dd)[0x564bbbf0e6dd]
[runnervmmklqx:06537] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f69f482a1ca]
[runnervmmklqx:06537] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f69f482a28b]
[runnervmmklqx:06537] [11] plumed_master(+0x15365)[0x564bbbf0f365]
[runnervmmklqx:06537] *** End of error message ***
</pre>
{% endraw %}

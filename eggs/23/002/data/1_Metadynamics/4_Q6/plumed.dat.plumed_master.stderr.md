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
[pkrvmq0rgcvqdmg:08711] *** Process received signal ***
[pkrvmq0rgcvqdmg:08711] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08711] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08711] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdfaea45330]
[pkrvmq0rgcvqdmg:08711] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdfaea9eb2c]
[pkrvmq0rgcvqdmg:08711] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdfaea4527e]
[pkrvmq0rgcvqdmg:08711] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdfaea288ff]
[pkrvmq0rgcvqdmg:08711] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdfaeea5ff5]
[pkrvmq0rgcvqdmg:08711] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdfaeebb0da]
[pkrvmq0rgcvqdmg:08711] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdfaeea5a55]
[pkrvmq0rgcvqdmg:08711] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdfaeea5a6f]
[pkrvmq0rgcvqdmg:08711] [ 8] plumed_master(+0x146dd)[0x56524a25e6dd]
[pkrvmq0rgcvqdmg:08711] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdfaea2a1ca]
[pkrvmq0rgcvqdmg:08711] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdfaea2a28b]
[pkrvmq0rgcvqdmg:08711] [11] plumed_master(+0x15365)[0x56524a25f365]
[pkrvmq0rgcvqdmg:08711] *** End of error message ***
</pre>
{% endraw %}

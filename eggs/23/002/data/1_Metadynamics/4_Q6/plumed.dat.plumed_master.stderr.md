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
[runnervmmtnos:33762] *** Process received signal ***
[runnervmmtnos:33762] Signal: Aborted (6)
[runnervmmtnos:33762] Signal code:  (-6)
[runnervmmtnos:33762] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f08a4845330]
[runnervmmtnos:33762] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f08a489eb2c]
[runnervmmtnos:33762] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f08a484527e]
[runnervmmtnos:33762] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f08a48288ff]
[runnervmmtnos:33762] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f08a4ca5ff5]
[runnervmmtnos:33762] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f08a4cbb0da]
[runnervmmtnos:33762] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f08a4ca5a55]
[runnervmmtnos:33762] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f08a4ca5a6f]
[runnervmmtnos:33762] [ 8] plumed_master(+0x146dd)[0x55f5dd17d6dd]
[runnervmmtnos:33762] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f08a482a1ca]
[runnervmmtnos:33762] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f08a482a28b]
[runnervmmtnos:33762] [11] plumed_master(+0x15365)[0x55f5dd17e365]
[runnervmmtnos:33762] *** End of error message ***
</pre>
{% endraw %}

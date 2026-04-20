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
[runnervmeorf1:06714] *** Process received signal ***
[runnervmeorf1:06714] Signal: Aborted (6)
[runnervmeorf1:06714] Signal code:  (-6)
[runnervmeorf1:06714] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa2fe45330]
[runnervmeorf1:06714] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa2fe9eb2c]
[runnervmeorf1:06714] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa2fe4527e]
[runnervmeorf1:06714] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa2fe288ff]
[runnervmeorf1:06714] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa302a5ff5]
[runnervmeorf1:06714] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa302bb0da]
[runnervmeorf1:06714] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa302a5a55]
[runnervmeorf1:06714] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa302a5a6f]
[runnervmeorf1:06714] [ 8] plumed_master(+0x146dd)[0x55ff943326dd]
[runnervmeorf1:06714] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa2fe2a1ca]
[runnervmeorf1:06714] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa2fe2a28b]
[runnervmeorf1:06714] [11] plumed_master(+0x15365)[0x55ff94333365]
[runnervmeorf1:06714] *** End of error message ***
</pre>
{% endraw %}

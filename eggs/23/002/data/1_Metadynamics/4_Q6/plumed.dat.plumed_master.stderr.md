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
[runnervmvrwv9:07219] *** Process received signal ***
[runnervmvrwv9:07219] Signal: Aborted (6)
[runnervmvrwv9:07219] Signal code:  (-6)
[runnervmvrwv9:07219] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f15fb445330]
[runnervmvrwv9:07219] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f15fb49eb2c]
[runnervmvrwv9:07219] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f15fb44527e]
[runnervmvrwv9:07219] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f15fb4288ff]
[runnervmvrwv9:07219] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f15fb8a5ff5]
[runnervmvrwv9:07219] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f15fb8bb0da]
[runnervmvrwv9:07219] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f15fb8a5a55]
[runnervmvrwv9:07219] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f15fb8a5a6f]
[runnervmvrwv9:07219] [ 8] plumed_master(+0x146dd)[0x560aac4d96dd]
[runnervmvrwv9:07219] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f15fb42a1ca]
[runnervmvrwv9:07219] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f15fb42a28b]
[runnervmvrwv9:07219] [11] plumed_master(+0x15365)[0x560aac4da365]
[runnervmvrwv9:07219] *** End of error message ***
</pre>
{% endraw %}

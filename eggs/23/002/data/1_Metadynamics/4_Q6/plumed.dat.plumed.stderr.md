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
[runnervmvrwv9:07203] *** Process received signal ***
[runnervmvrwv9:07203] Signal: Aborted (6)
[runnervmvrwv9:07203] Signal code:  (-6)
[runnervmvrwv9:07203] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d7fc45330]
[runnervmvrwv9:07203] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d7fc9eb2c]
[runnervmvrwv9:07203] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d7fc4527e]
[runnervmvrwv9:07203] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d7fc288ff]
[runnervmvrwv9:07203] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d800a5ff5]
[runnervmvrwv9:07203] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d800bb0da]
[runnervmvrwv9:07203] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d800a5a55]
[runnervmvrwv9:07203] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d800a5a6f]
[runnervmvrwv9:07203] [ 8] plumed(+0x146dd)[0x55b0ba0e36dd]
[runnervmvrwv9:07203] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d7fc2a1ca]
[runnervmvrwv9:07203] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d7fc2a28b]
[runnervmvrwv9:07203] [11] plumed(+0x15365)[0x55b0ba0e4365]
[runnervmvrwv9:07203] *** End of error message ***
</pre>
{% endraw %}

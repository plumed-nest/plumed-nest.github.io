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
[runnervmmtnos:33746] *** Process received signal ***
[runnervmmtnos:33746] Signal: Aborted (6)
[runnervmmtnos:33746] Signal code:  (-6)
[runnervmmtnos:33746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8843645330]
[runnervmmtnos:33746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f884369eb2c]
[runnervmmtnos:33746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f884364527e]
[runnervmmtnos:33746] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88436288ff]
[runnervmmtnos:33746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8843aa5ff5]
[runnervmmtnos:33746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8843abb0da]
[runnervmmtnos:33746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8843aa5a55]
[runnervmmtnos:33746] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8843aa5a6f]
[runnervmmtnos:33746] [ 8] plumed(+0x146dd)[0x55804bf226dd]
[runnervmmtnos:33746] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f884362a1ca]
[runnervmmtnos:33746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f884362a28b]
[runnervmmtnos:33746] [11] plumed(+0x15365)[0x55804bf23365]
[runnervmmtnos:33746] *** End of error message ***
</pre>
{% endraw %}

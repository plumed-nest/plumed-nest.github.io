**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmw9dnm:06043] *** Process received signal ***
[runnervmw9dnm:06043] Signal: Aborted (6)
[runnervmw9dnm:06043] Signal code:  (-6)
[runnervmw9dnm:06043] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f866da45330]
[runnervmw9dnm:06043] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f866da9eb2c]
[runnervmw9dnm:06043] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f866da4527e]
[runnervmw9dnm:06043] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f866da288ff]
[runnervmw9dnm:06043] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f866dea5ff5]
[runnervmw9dnm:06043] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f866debb0da]
[runnervmw9dnm:06043] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f866dea5a55]
[runnervmw9dnm:06043] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f866dea5a6f]
[runnervmw9dnm:06043] [ 8] plumed(+0x146dd)[0x5598b49c96dd]
[runnervmw9dnm:06043] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f866da2a1ca]
[runnervmw9dnm:06043] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f866da2a28b]
[runnervmw9dnm:06043] [11] plumed(+0x15365)[0x5598b49ca365]
[runnervmw9dnm:06043] *** End of error message ***
</pre>
{% endraw %}

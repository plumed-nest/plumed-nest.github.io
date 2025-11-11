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
[runnervmw9dnm:07175] *** Process received signal ***
[runnervmw9dnm:07175] Signal: Aborted (6)
[runnervmw9dnm:07175] Signal code:  (-6)
[runnervmw9dnm:07175] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c5ea45330]
[runnervmw9dnm:07175] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c5ea9eb2c]
[runnervmw9dnm:07175] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c5ea4527e]
[runnervmw9dnm:07175] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c5ea288ff]
[runnervmw9dnm:07175] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c5eea5ff5]
[runnervmw9dnm:07175] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c5eebb0da]
[runnervmw9dnm:07175] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c5eea5a55]
[runnervmw9dnm:07175] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c5eea5a6f]
[runnervmw9dnm:07175] [ 8] plumed(+0x146dd)[0x563dd61b96dd]
[runnervmw9dnm:07175] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c5ea2a1ca]
[runnervmw9dnm:07175] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c5ea2a28b]
[runnervmw9dnm:07175] [11] plumed(+0x15365)[0x563dd61ba365]
[runnervmw9dnm:07175] *** End of error message ***
</pre>
{% endraw %}

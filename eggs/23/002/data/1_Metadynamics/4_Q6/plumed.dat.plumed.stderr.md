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
[runnervmmklqx:06521] *** Process received signal ***
[runnervmmklqx:06521] Signal: Aborted (6)
[runnervmmklqx:06521] Signal code:  (-6)
[runnervmmklqx:06521] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8d5045330]
[runnervmmklqx:06521] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8d509eb2c]
[runnervmmklqx:06521] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8d504527e]
[runnervmmklqx:06521] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8d50288ff]
[runnervmmklqx:06521] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8d54a5ff5]
[runnervmmklqx:06521] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8d54bb0da]
[runnervmmklqx:06521] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8d54a5a55]
[runnervmmklqx:06521] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8d54a5a6f]
[runnervmmklqx:06521] [ 8] plumed(+0x146dd)[0x5595fab2c6dd]
[runnervmmklqx:06521] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8d502a1ca]
[runnervmmklqx:06521] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8d502a28b]
[runnervmmklqx:06521] [11] plumed(+0x15365)[0x5595fab2d365]
[runnervmmklqx:06521] *** End of error message ***
</pre>
{% endraw %}

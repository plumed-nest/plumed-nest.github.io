**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[fv-az1665-105:07722] *** Process received signal ***
[fv-az1665-105:07722] Signal: Aborted (6)
[fv-az1665-105:07722] Signal code:  (-6)
[fv-az1665-105:07722] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f40dfe45330]
[fv-az1665-105:07722] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f40dfe9eb2c]
[fv-az1665-105:07722] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f40dfe4527e]
[fv-az1665-105:07722] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f40dfe288ff]
[fv-az1665-105:07722] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f40e02a5ff5]
[fv-az1665-105:07722] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f40e02bb0da]
[fv-az1665-105:07722] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f40e02a5a55]
[fv-az1665-105:07722] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f40e02a5a6f]
[fv-az1665-105:07722] [ 8] plumed(+0x146dd)[0x5597219ac6dd]
[fv-az1665-105:07722] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f40dfe2a1ca]
[fv-az1665-105:07722] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f40dfe2a28b]
[fv-az1665-105:07722] [11] plumed(+0x15365)[0x5597219ad365]
[fv-az1665-105:07722] *** End of error message ***
</pre>
{% endraw %}

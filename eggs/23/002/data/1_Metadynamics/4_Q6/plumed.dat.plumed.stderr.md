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
[fv-az1267-279:64408] *** Process received signal ***
[fv-az1267-279:64408] Signal: Aborted (6)
[fv-az1267-279:64408] Signal code:  (-6)
[fv-az1267-279:64408] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9eb7e45330]
[fv-az1267-279:64408] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9eb7e9eb2c]
[fv-az1267-279:64408] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9eb7e4527e]
[fv-az1267-279:64408] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9eb7e288ff]
[fv-az1267-279:64408] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9eb82a5ff5]
[fv-az1267-279:64408] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9eb82bb0da]
[fv-az1267-279:64408] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9eb82a5a55]
[fv-az1267-279:64408] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9eb82a5a6f]
[fv-az1267-279:64408] [ 8] plumed(+0x146dd)[0x55c76462a6dd]
[fv-az1267-279:64408] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9eb7e2a1ca]
[fv-az1267-279:64408] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9eb7e2a28b]
[fv-az1267-279:64408] [11] plumed(+0x15365)[0x55c76462b365]
[fv-az1267-279:64408] *** End of error message ***
</pre>
{% endraw %}

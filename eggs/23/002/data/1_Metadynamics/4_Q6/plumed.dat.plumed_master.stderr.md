**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[fv-az2209-645:61734] *** Process received signal ***
[fv-az2209-645:61734] Signal: Aborted (6)
[fv-az2209-645:61734] Signal code:  (-6)
[fv-az2209-645:61734] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b9e845330]
[fv-az2209-645:61734] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b9e89eb2c]
[fv-az2209-645:61734] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b9e84527e]
[fv-az2209-645:61734] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b9e8288ff]
[fv-az2209-645:61734] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b9eca5ff5]
[fv-az2209-645:61734] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b9ecbb0da]
[fv-az2209-645:61734] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b9eca5a55]
[fv-az2209-645:61734] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b9eca5a6f]
[fv-az2209-645:61734] [ 8] plumed_master(+0x146dd)[0x55f1d277a6dd]
[fv-az2209-645:61734] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b9e82a1ca]
[fv-az2209-645:61734] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b9e82a28b]
[fv-az2209-645:61734] [11] plumed_master(+0x15365)[0x55f1d277b365]
[fv-az2209-645:61734] *** End of error message ***
</pre>
{% endraw %}

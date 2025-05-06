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
[fv-az2209-645:61718] *** Process received signal ***
[fv-az2209-645:61718] Signal: Aborted (6)
[fv-az2209-645:61718] Signal code:  (-6)
[fv-az2209-645:61718] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5376a45330]
[fv-az2209-645:61718] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5376a9eb2c]
[fv-az2209-645:61718] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5376a4527e]
[fv-az2209-645:61718] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5376a288ff]
[fv-az2209-645:61718] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5376ea5ff5]
[fv-az2209-645:61718] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5376ebb0da]
[fv-az2209-645:61718] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5376ea5a55]
[fv-az2209-645:61718] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5376ea5a6f]
[fv-az2209-645:61718] [ 8] plumed(+0x146dd)[0x55b9bfe126dd]
[fv-az2209-645:61718] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5376a2a1ca]
[fv-az2209-645:61718] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5376a2a28b]
[fv-az2209-645:61718] [11] plumed(+0x15365)[0x55b9bfe13365]
[fv-az2209-645:61718] *** End of error message ***
</pre>
{% endraw %}

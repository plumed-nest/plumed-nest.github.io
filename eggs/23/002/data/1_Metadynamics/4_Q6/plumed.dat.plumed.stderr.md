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
[pkrvmpptgkbjq6m:08939] *** Process received signal ***
[pkrvmpptgkbjq6m:08939] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08939] Signal code:  (-6)
[pkrvmpptgkbjq6m:08939] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc3d845330]
[pkrvmpptgkbjq6m:08939] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc3d89eb2c]
[pkrvmpptgkbjq6m:08939] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc3d84527e]
[pkrvmpptgkbjq6m:08939] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc3d8288ff]
[pkrvmpptgkbjq6m:08939] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc3dca5ff5]
[pkrvmpptgkbjq6m:08939] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc3dcbb0da]
[pkrvmpptgkbjq6m:08939] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc3dca5a55]
[pkrvmpptgkbjq6m:08939] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc3dca5a6f]
[pkrvmpptgkbjq6m:08939] [ 8] plumed(+0x146dd)[0x5616bbe0e6dd]
[pkrvmpptgkbjq6m:08939] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc3d82a1ca]
[pkrvmpptgkbjq6m:08939] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc3d82a28b]
[pkrvmpptgkbjq6m:08939] [11] plumed(+0x15365)[0x5616bbe0f365]
[pkrvmpptgkbjq6m:08939] *** End of error message ***
</pre>
{% endraw %}

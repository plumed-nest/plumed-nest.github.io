**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s29 : cannot understand the following words from the input line : LOWMEM
[pkrvmpptgkbjq6m:08955] *** Process received signal ***
[pkrvmpptgkbjq6m:08955] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08955] Signal code:  (-6)
[pkrvmpptgkbjq6m:08955] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb001c45330]
[pkrvmpptgkbjq6m:08955] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb001c9eb2c]
[pkrvmpptgkbjq6m:08955] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb001c4527e]
[pkrvmpptgkbjq6m:08955] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb001c288ff]
[pkrvmpptgkbjq6m:08955] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb0020a5ff5]
[pkrvmpptgkbjq6m:08955] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb0020bb0da]
[pkrvmpptgkbjq6m:08955] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb0020a5a55]
[pkrvmpptgkbjq6m:08955] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb0020a5a6f]
[pkrvmpptgkbjq6m:08955] [ 8] plumed_master(+0x146dd)[0x55b9976af6dd]
[pkrvmpptgkbjq6m:08955] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb001c2a1ca]
[pkrvmpptgkbjq6m:08955] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb001c2a28b]
[pkrvmpptgkbjq6m:08955] [11] plumed_master(+0x15365)[0x55b9976b0365]
[pkrvmpptgkbjq6m:08955] *** End of error message ***
</pre>
{% endraw %}

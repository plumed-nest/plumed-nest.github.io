**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmf6wy0o8zjz:34994] *** Process received signal ***
[pkrvmf6wy0o8zjz:34994] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:34994] Signal code:  (-6)
[pkrvmf6wy0o8zjz:34994] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d00c45330]
[pkrvmf6wy0o8zjz:34994] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d00c9eb2c]
[pkrvmf6wy0o8zjz:34994] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d00c4527e]
[pkrvmf6wy0o8zjz:34994] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d00c288ff]
[pkrvmf6wy0o8zjz:34994] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d010a5ff5]
[pkrvmf6wy0o8zjz:34994] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d010bb0da]
[pkrvmf6wy0o8zjz:34994] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d010a5a55]
[pkrvmf6wy0o8zjz:34994] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d010a5a6f]
[pkrvmf6wy0o8zjz:34994] [ 8] plumed_master(+0x146dd)[0x561c660bd6dd]
[pkrvmf6wy0o8zjz:34994] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d00c2a1ca]
[pkrvmf6wy0o8zjz:34994] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d00c2a28b]
[pkrvmf6wy0o8zjz:34994] [11] plumed_master(+0x15365)[0x561c660be365]
[pkrvmf6wy0o8zjz:34994] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmf6wy0o8zjz:37044] *** Process received signal ***
[pkrvmf6wy0o8zjz:37044] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37044] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6ce6645330]
[pkrvmf6wy0o8zjz:37044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6ce669eb2c]
[pkrvmf6wy0o8zjz:37044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6ce664527e]
[pkrvmf6wy0o8zjz:37044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6ce66288ff]
[pkrvmf6wy0o8zjz:37044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6ce6aa5ff5]
[pkrvmf6wy0o8zjz:37044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6ce6abb0da]
[pkrvmf6wy0o8zjz:37044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6ce6aa5a55]
[pkrvmf6wy0o8zjz:37044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6ce6aa5a6f]
[pkrvmf6wy0o8zjz:37044] [ 8] plumed_master(+0x146dd)[0x55b41fb756dd]
[pkrvmf6wy0o8zjz:37044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6ce662a1ca]
[pkrvmf6wy0o8zjz:37044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6ce662a28b]
[pkrvmf6wy0o8zjz:37044] [11] plumed_master(+0x15365)[0x55b41fb76365]
[pkrvmf6wy0o8zjz:37044] *** End of error message ***
</pre>
{% endraw %}

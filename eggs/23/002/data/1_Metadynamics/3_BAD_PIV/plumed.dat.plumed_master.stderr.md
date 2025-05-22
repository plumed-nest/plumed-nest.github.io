**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmf6wy0o8zjz:37147] *** Process received signal ***
[pkrvmf6wy0o8zjz:37147] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37147] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37147] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa082845330]
[pkrvmf6wy0o8zjz:37147] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa08289eb2c]
[pkrvmf6wy0o8zjz:37147] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa08284527e]
[pkrvmf6wy0o8zjz:37147] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa0828288ff]
[pkrvmf6wy0o8zjz:37147] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa082ca5ff5]
[pkrvmf6wy0o8zjz:37147] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa082cbb0da]
[pkrvmf6wy0o8zjz:37147] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa082ca5a55]
[pkrvmf6wy0o8zjz:37147] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa082ca5a6f]
[pkrvmf6wy0o8zjz:37147] [ 8] plumed_master(+0x146dd)[0x5602332066dd]
[pkrvmf6wy0o8zjz:37147] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa08282a1ca]
[pkrvmf6wy0o8zjz:37147] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa08282a28b]
[pkrvmf6wy0o8zjz:37147] [11] plumed_master(+0x15365)[0x560233207365]
[pkrvmf6wy0o8zjz:37147] *** End of error message ***
</pre>
{% endraw %}

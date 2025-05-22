**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmf6wy0o8zjz:37251] *** Process received signal ***
[pkrvmf6wy0o8zjz:37251] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37251] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37251] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4689245330]
[pkrvmf6wy0o8zjz:37251] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f468929eb2c]
[pkrvmf6wy0o8zjz:37251] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f468924527e]
[pkrvmf6wy0o8zjz:37251] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f46892288ff]
[pkrvmf6wy0o8zjz:37251] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f46896a5ff5]
[pkrvmf6wy0o8zjz:37251] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f46896bb0da]
[pkrvmf6wy0o8zjz:37251] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f46896a5a55]
[pkrvmf6wy0o8zjz:37251] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f46896a5a6f]
[pkrvmf6wy0o8zjz:37251] [ 8] plumed_master(+0x146dd)[0x562f46b0b6dd]
[pkrvmf6wy0o8zjz:37251] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f468922a1ca]
[pkrvmf6wy0o8zjz:37251] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f468922a28b]
[pkrvmf6wy0o8zjz:37251] [11] plumed_master(+0x15365)[0x562f46b0c365]
[pkrvmf6wy0o8zjz:37251] *** End of error message ***
</pre>
{% endraw %}

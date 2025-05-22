**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmf6wy0o8zjz:35331] *** Process received signal ***
[pkrvmf6wy0o8zjz:35331] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:35331] Signal code:  (-6)
[pkrvmf6wy0o8zjz:35331] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa81c45330]
[pkrvmf6wy0o8zjz:35331] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa81c9eb2c]
[pkrvmf6wy0o8zjz:35331] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa81c4527e]
[pkrvmf6wy0o8zjz:35331] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa81c288ff]
[pkrvmf6wy0o8zjz:35331] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa820a5ff5]
[pkrvmf6wy0o8zjz:35331] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa820bb0da]
[pkrvmf6wy0o8zjz:35331] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa820a5a55]
[pkrvmf6wy0o8zjz:35331] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa820a5a6f]
[pkrvmf6wy0o8zjz:35331] [ 8] plumed(+0x146dd)[0x55b3543a06dd]
[pkrvmf6wy0o8zjz:35331] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa81c2a1ca]
[pkrvmf6wy0o8zjz:35331] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa81c2a28b]
[pkrvmf6wy0o8zjz:35331] [11] plumed(+0x15365)[0x55b3543a1365]
[pkrvmf6wy0o8zjz:35331] *** End of error message ***
</pre>
{% endraw %}

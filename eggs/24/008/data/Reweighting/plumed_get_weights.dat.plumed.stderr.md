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
[pkrvmf6wy0o8zjz:62319] *** Process received signal ***
[pkrvmf6wy0o8zjz:62319] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62319] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62319] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23f8c45330]
[pkrvmf6wy0o8zjz:62319] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23f8c9eb2c]
[pkrvmf6wy0o8zjz:62319] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23f8c4527e]
[pkrvmf6wy0o8zjz:62319] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23f8c288ff]
[pkrvmf6wy0o8zjz:62319] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23f90a5ff5]
[pkrvmf6wy0o8zjz:62319] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23f90bb0da]
[pkrvmf6wy0o8zjz:62319] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23f90a5a55]
[pkrvmf6wy0o8zjz:62319] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23f90a5a6f]
[pkrvmf6wy0o8zjz:62319] [ 8] plumed(+0x146dd)[0x5562e99f46dd]
[pkrvmf6wy0o8zjz:62319] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23f8c2a1ca]
[pkrvmf6wy0o8zjz:62319] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23f8c2a28b]
[pkrvmf6wy0o8zjz:62319] [11] plumed(+0x15365)[0x5562e99f5365]
[pkrvmf6wy0o8zjz:62319] *** End of error message ***
</pre>
{% endraw %}

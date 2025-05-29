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
[pkrvmf6wy0o8zjz:63718] *** Process received signal ***
[pkrvmf6wy0o8zjz:63718] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:63718] Signal code:  (-6)
[pkrvmf6wy0o8zjz:63718] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa9b1a45330]
[pkrvmf6wy0o8zjz:63718] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa9b1a9eb2c]
[pkrvmf6wy0o8zjz:63718] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa9b1a4527e]
[pkrvmf6wy0o8zjz:63718] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa9b1a288ff]
[pkrvmf6wy0o8zjz:63718] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa9b1ea5ff5]
[pkrvmf6wy0o8zjz:63718] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa9b1ebb0da]
[pkrvmf6wy0o8zjz:63718] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa9b1ea5a55]
[pkrvmf6wy0o8zjz:63718] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa9b1ea5a6f]
[pkrvmf6wy0o8zjz:63718] [ 8] plumed_master(+0x146dd)[0x5571b88af6dd]
[pkrvmf6wy0o8zjz:63718] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa9b1a2a1ca]
[pkrvmf6wy0o8zjz:63718] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa9b1a2a28b]
[pkrvmf6wy0o8zjz:63718] [11] plumed_master(+0x15365)[0x5571b88b0365]
[pkrvmf6wy0o8zjz:63718] *** End of error message ***
</pre>
{% endraw %}

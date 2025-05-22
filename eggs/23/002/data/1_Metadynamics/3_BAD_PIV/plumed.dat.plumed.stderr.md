**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmf6wy0o8zjz:37132] *** Process received signal ***
[pkrvmf6wy0o8zjz:37132] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37132] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37132] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd476045330]
[pkrvmf6wy0o8zjz:37132] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd47609eb2c]
[pkrvmf6wy0o8zjz:37132] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd47604527e]
[pkrvmf6wy0o8zjz:37132] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4760288ff]
[pkrvmf6wy0o8zjz:37132] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4764a5ff5]
[pkrvmf6wy0o8zjz:37132] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4764bb0da]
[pkrvmf6wy0o8zjz:37132] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4764a5a55]
[pkrvmf6wy0o8zjz:37132] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4764a5a6f]
[pkrvmf6wy0o8zjz:37132] [ 8] plumed(+0x146dd)[0x560cbecf06dd]
[pkrvmf6wy0o8zjz:37132] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd47602a1ca]
[pkrvmf6wy0o8zjz:37132] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd47602a28b]
[pkrvmf6wy0o8zjz:37132] [11] plumed(+0x15365)[0x560cbecf1365]
[pkrvmf6wy0o8zjz:37132] *** End of error message ***
</pre>
{% endraw %}

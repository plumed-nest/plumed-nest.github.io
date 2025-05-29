**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmf6wy0o8zjz:62371] *** Process received signal ***
[pkrvmf6wy0o8zjz:62371] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62371] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62371] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe108a45330]
[pkrvmf6wy0o8zjz:62371] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe108a9eb2c]
[pkrvmf6wy0o8zjz:62371] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe108a4527e]
[pkrvmf6wy0o8zjz:62371] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe108a288ff]
[pkrvmf6wy0o8zjz:62371] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe108ea5ff5]
[pkrvmf6wy0o8zjz:62371] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe108ebb0da]
[pkrvmf6wy0o8zjz:62371] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe108ea5a55]
[pkrvmf6wy0o8zjz:62371] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe108ea5a6f]
[pkrvmf6wy0o8zjz:62371] [ 8] plumed(+0x146dd)[0x55ac85c4a6dd]
[pkrvmf6wy0o8zjz:62371] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe108a2a1ca]
[pkrvmf6wy0o8zjz:62371] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe108a2a28b]
[pkrvmf6wy0o8zjz:62371] [11] plumed(+0x15365)[0x55ac85c4b365]
[pkrvmf6wy0o8zjz:62371] *** End of error message ***
</pre>
{% endraw %}

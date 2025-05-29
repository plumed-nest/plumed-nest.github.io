**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:64001] *** Process received signal ***
[pkrvmf6wy0o8zjz:64001] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64001] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64001] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3afc245330]
[pkrvmf6wy0o8zjz:64001] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3afc29eb2c]
[pkrvmf6wy0o8zjz:64001] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3afc24527e]
[pkrvmf6wy0o8zjz:64001] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3afc2288ff]
[pkrvmf6wy0o8zjz:64001] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3afc6a5ff5]
[pkrvmf6wy0o8zjz:64001] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3afc6bb0da]
[pkrvmf6wy0o8zjz:64001] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3afc6a5a55]
[pkrvmf6wy0o8zjz:64001] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3afc6a5a6f]
[pkrvmf6wy0o8zjz:64001] [ 8] plumed_master(+0x146dd)[0x5565bd9e46dd]
[pkrvmf6wy0o8zjz:64001] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3afc22a1ca]
[pkrvmf6wy0o8zjz:64001] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3afc22a28b]
[pkrvmf6wy0o8zjz:64001] [11] plumed_master(+0x15365)[0x5565bd9e5365]
[pkrvmf6wy0o8zjz:64001] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @90 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:36570] *** Process received signal ***
[pkrvmf6wy0o8zjz:36570] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:36570] Signal code:  (-6)
[pkrvmf6wy0o8zjz:36570] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6260845330]
[pkrvmf6wy0o8zjz:36570] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f626089eb2c]
[pkrvmf6wy0o8zjz:36570] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f626084527e]
[pkrvmf6wy0o8zjz:36570] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62608288ff]
[pkrvmf6wy0o8zjz:36570] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6260ca5ff5]
[pkrvmf6wy0o8zjz:36570] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6260cbb0da]
[pkrvmf6wy0o8zjz:36570] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6260ca5a55]
[pkrvmf6wy0o8zjz:36570] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6260ca5a6f]
[pkrvmf6wy0o8zjz:36570] [ 8] plumed_master(+0x146dd)[0x563e957016dd]
[pkrvmf6wy0o8zjz:36570] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f626082a1ca]
[pkrvmf6wy0o8zjz:36570] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f626082a28b]
[pkrvmf6wy0o8zjz:36570] [11] plumed_master(+0x15365)[0x563e95702365]
[pkrvmf6wy0o8zjz:36570] *** End of error message ***
</pre>
{% endraw %}

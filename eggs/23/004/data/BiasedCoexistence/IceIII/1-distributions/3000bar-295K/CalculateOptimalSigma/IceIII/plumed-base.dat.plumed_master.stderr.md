**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:63924] *** Process received signal ***
[pkrvmf6wy0o8zjz:63924] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:63924] Signal code:  (-6)
[pkrvmf6wy0o8zjz:63924] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb262045330]
[pkrvmf6wy0o8zjz:63924] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb26209eb2c]
[pkrvmf6wy0o8zjz:63924] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb26204527e]
[pkrvmf6wy0o8zjz:63924] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2620288ff]
[pkrvmf6wy0o8zjz:63924] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb2624a5ff5]
[pkrvmf6wy0o8zjz:63924] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb2624bb0da]
[pkrvmf6wy0o8zjz:63924] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb2624a5a55]
[pkrvmf6wy0o8zjz:63924] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb2624a5a6f]
[pkrvmf6wy0o8zjz:63924] [ 8] plumed_master(+0x146dd)[0x563fd601d6dd]
[pkrvmf6wy0o8zjz:63924] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb26202a1ca]
[pkrvmf6wy0o8zjz:63924] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb26202a28b]
[pkrvmf6wy0o8zjz:63924] [11] plumed_master(+0x15365)[0x563fd601e365]
[pkrvmf6wy0o8zjz:63924] *** End of error message ***
</pre>
{% endraw %}

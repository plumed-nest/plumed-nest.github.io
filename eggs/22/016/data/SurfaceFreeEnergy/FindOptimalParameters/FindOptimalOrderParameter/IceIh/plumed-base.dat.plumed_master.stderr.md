**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @58 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:34956] *** Process received signal ***
[pkrvmf6wy0o8zjz:34956] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:34956] Signal code:  (-6)
[pkrvmf6wy0o8zjz:34956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f079b045330]
[pkrvmf6wy0o8zjz:34956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f079b09eb2c]
[pkrvmf6wy0o8zjz:34956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f079b04527e]
[pkrvmf6wy0o8zjz:34956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f079b0288ff]
[pkrvmf6wy0o8zjz:34956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f079b4a5ff5]
[pkrvmf6wy0o8zjz:34956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f079b4bb0da]
[pkrvmf6wy0o8zjz:34956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f079b4a5a55]
[pkrvmf6wy0o8zjz:34956] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f079b4a5a6f]
[pkrvmf6wy0o8zjz:34956] [ 8] plumed_master(+0x146dd)[0x55724694e6dd]
[pkrvmf6wy0o8zjz:34956] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f079b02a1ca]
[pkrvmf6wy0o8zjz:34956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f079b02a28b]
[pkrvmf6wy0o8zjz:34956] [11] plumed_master(+0x15365)[0x55724694f365]
[pkrvmf6wy0o8zjz:34956] *** End of error message ***
</pre>
{% endraw %}

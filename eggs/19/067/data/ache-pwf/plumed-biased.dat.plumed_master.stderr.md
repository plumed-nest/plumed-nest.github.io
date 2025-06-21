**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmxyh4eaekms:10454] *** Process received signal ***
[pkrvmxyh4eaekms:10454] Signal: Aborted (6)
[pkrvmxyh4eaekms:10454] Signal code:  (-6)
[pkrvmxyh4eaekms:10454] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1280045330]
[pkrvmxyh4eaekms:10454] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f128009eb2c]
[pkrvmxyh4eaekms:10454] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f128004527e]
[pkrvmxyh4eaekms:10454] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12800288ff]
[pkrvmxyh4eaekms:10454] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12804a5ff5]
[pkrvmxyh4eaekms:10454] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12804bb0da]
[pkrvmxyh4eaekms:10454] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12804a5a55]
[pkrvmxyh4eaekms:10454] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12804a5a6f]
[pkrvmxyh4eaekms:10454] [ 8] plumed_master(+0x146dd)[0x5652e06ef6dd]
[pkrvmxyh4eaekms:10454] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f128002a1ca]
[pkrvmxyh4eaekms:10454] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f128002a28b]
[pkrvmxyh4eaekms:10454] [11] plumed_master(+0x15365)[0x5652e06f0365]
[pkrvmxyh4eaekms:10454] *** End of error message ***
</pre>
{% endraw %}

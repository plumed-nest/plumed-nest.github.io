**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmxyh4eaekms:10533] *** Process received signal ***
[pkrvmxyh4eaekms:10533] Signal: Aborted (6)
[pkrvmxyh4eaekms:10533] Signal code:  (-6)
[pkrvmxyh4eaekms:10533] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9e65045330]
[pkrvmxyh4eaekms:10533] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9e6509eb2c]
[pkrvmxyh4eaekms:10533] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9e6504527e]
[pkrvmxyh4eaekms:10533] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9e650288ff]
[pkrvmxyh4eaekms:10533] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9e654a5ff5]
[pkrvmxyh4eaekms:10533] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9e654bb0da]
[pkrvmxyh4eaekms:10533] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9e654a5a55]
[pkrvmxyh4eaekms:10533] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9e654a5a6f]
[pkrvmxyh4eaekms:10533] [ 8] plumed_master(+0x146dd)[0x55ff32e516dd]
[pkrvmxyh4eaekms:10533] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9e6502a1ca]
[pkrvmxyh4eaekms:10533] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9e6502a28b]
[pkrvmxyh4eaekms:10533] [11] plumed_master(+0x15365)[0x55ff32e52365]
[pkrvmxyh4eaekms:10533] *** End of error message ***
</pre>
{% endraw %}

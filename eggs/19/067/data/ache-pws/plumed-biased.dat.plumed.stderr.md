**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmxyh4eaekms:10517] *** Process received signal ***
[pkrvmxyh4eaekms:10517] Signal: Aborted (6)
[pkrvmxyh4eaekms:10517] Signal code:  (-6)
[pkrvmxyh4eaekms:10517] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fabf9e45330]
[pkrvmxyh4eaekms:10517] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fabf9e9eb2c]
[pkrvmxyh4eaekms:10517] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fabf9e4527e]
[pkrvmxyh4eaekms:10517] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fabf9e288ff]
[pkrvmxyh4eaekms:10517] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fabfa2a5ff5]
[pkrvmxyh4eaekms:10517] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fabfa2bb0da]
[pkrvmxyh4eaekms:10517] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fabfa2a5a55]
[pkrvmxyh4eaekms:10517] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fabfa2a5a6f]
[pkrvmxyh4eaekms:10517] [ 8] plumed(+0x146dd)[0x562801f9a6dd]
[pkrvmxyh4eaekms:10517] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fabf9e2a1ca]
[pkrvmxyh4eaekms:10517] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fabf9e2a28b]
[pkrvmxyh4eaekms:10517] [11] plumed(+0x15365)[0x562801f9b365]
[pkrvmxyh4eaekms:10517] *** End of error message ***
</pre>
{% endraw %}

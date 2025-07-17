**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmq0rgcvqdmg:12517] *** Process received signal ***
[pkrvmq0rgcvqdmg:12517] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12517] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12517] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f07aa245330]
[pkrvmq0rgcvqdmg:12517] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f07aa29eb2c]
[pkrvmq0rgcvqdmg:12517] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f07aa24527e]
[pkrvmq0rgcvqdmg:12517] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07aa2288ff]
[pkrvmq0rgcvqdmg:12517] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07aa6a5ff5]
[pkrvmq0rgcvqdmg:12517] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07aa6bb0da]
[pkrvmq0rgcvqdmg:12517] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07aa6a5a55]
[pkrvmq0rgcvqdmg:12517] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07aa6a5a6f]
[pkrvmq0rgcvqdmg:12517] [ 8] plumed(+0x146dd)[0x55c4b372b6dd]
[pkrvmq0rgcvqdmg:12517] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f07aa22a1ca]
[pkrvmq0rgcvqdmg:12517] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f07aa22a28b]
[pkrvmq0rgcvqdmg:12517] [11] plumed(+0x15365)[0x55c4b372c365]
[pkrvmq0rgcvqdmg:12517] *** End of error message ***
</pre>
{% endraw %}

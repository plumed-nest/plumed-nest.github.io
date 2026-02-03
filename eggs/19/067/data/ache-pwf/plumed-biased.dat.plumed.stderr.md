**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmkj6or:11687] *** Process received signal ***
[runnervmkj6or:11687] Signal: Aborted (6)
[runnervmkj6or:11687] Signal code:  (-6)
[runnervmkj6or:11687] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8a70045330]
[runnervmkj6or:11687] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8a7009eb2c]
[runnervmkj6or:11687] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8a7004527e]
[runnervmkj6or:11687] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8a700288ff]
[runnervmkj6or:11687] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8a704a5ff5]
[runnervmkj6or:11687] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8a704bb0da]
[runnervmkj6or:11687] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8a704a5a55]
[runnervmkj6or:11687] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8a704a5a6f]
[runnervmkj6or:11687] [ 8] plumed(+0x146dd)[0x55781e5106dd]
[runnervmkj6or:11687] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8a7002a1ca]
[runnervmkj6or:11687] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8a7002a28b]
[runnervmkj6or:11687] [11] plumed(+0x15365)[0x55781e511365]
[runnervmkj6or:11687] *** End of error message ***
</pre>
{% endraw %}

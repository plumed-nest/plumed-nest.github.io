**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmq0rgcvqdmg:12533] *** Process received signal ***
[pkrvmq0rgcvqdmg:12533] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12533] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12533] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbb06e45330]
[pkrvmq0rgcvqdmg:12533] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbb06e9eb2c]
[pkrvmq0rgcvqdmg:12533] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbb06e4527e]
[pkrvmq0rgcvqdmg:12533] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbb06e288ff]
[pkrvmq0rgcvqdmg:12533] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbb072a5ff5]
[pkrvmq0rgcvqdmg:12533] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbb072bb0da]
[pkrvmq0rgcvqdmg:12533] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbb072a5a55]
[pkrvmq0rgcvqdmg:12533] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbb072a5a6f]
[pkrvmq0rgcvqdmg:12533] [ 8] plumed_master(+0x146dd)[0x55c737e936dd]
[pkrvmq0rgcvqdmg:12533] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbb06e2a1ca]
[pkrvmq0rgcvqdmg:12533] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbb06e2a28b]
[pkrvmq0rgcvqdmg:12533] [11] plumed_master(+0x15365)[0x55c737e94365]
[pkrvmq0rgcvqdmg:12533] *** End of error message ***
</pre>
{% endraw %}

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
[pkrvmq0rgcvqdmg:10288] *** Process received signal ***
[pkrvmq0rgcvqdmg:10288] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:10288] Signal code:  (-6)
[pkrvmq0rgcvqdmg:10288] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4e4445330]
[pkrvmq0rgcvqdmg:10288] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4e449eb2c]
[pkrvmq0rgcvqdmg:10288] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4e444527e]
[pkrvmq0rgcvqdmg:10288] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4e44288ff]
[pkrvmq0rgcvqdmg:10288] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4e48a5ff5]
[pkrvmq0rgcvqdmg:10288] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4e48bb0da]
[pkrvmq0rgcvqdmg:10288] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4e48a5a55]
[pkrvmq0rgcvqdmg:10288] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4e48a5a6f]
[pkrvmq0rgcvqdmg:10288] [ 8] plumed(+0x146dd)[0x55ab9f85b6dd]
[pkrvmq0rgcvqdmg:10288] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4e442a1ca]
[pkrvmq0rgcvqdmg:10288] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4e442a28b]
[pkrvmq0rgcvqdmg:10288] [11] plumed(+0x15365)[0x55ab9f85c365]
[pkrvmq0rgcvqdmg:10288] *** End of error message ***
</pre>
{% endraw %}

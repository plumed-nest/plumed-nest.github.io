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
[runnervm0kj6c:11312] *** Process received signal ***
[runnervm0kj6c:11312] Signal: Aborted (6)
[runnervm0kj6c:11312] Signal code:  (-6)
[runnervm0kj6c:11312] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa95ae45330]
[runnervm0kj6c:11312] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa95ae9eb2c]
[runnervm0kj6c:11312] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa95ae4527e]
[runnervm0kj6c:11312] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa95ae288ff]
[runnervm0kj6c:11312] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa95b2a5ff5]
[runnervm0kj6c:11312] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa95b2bb0da]
[runnervm0kj6c:11312] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa95b2a5a55]
[runnervm0kj6c:11312] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa95b2a5a6f]
[runnervm0kj6c:11312] [ 8] plumed(+0x146dd)[0x560889d536dd]
[runnervm0kj6c:11312] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa95ae2a1ca]
[runnervm0kj6c:11312] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa95ae2a28b]
[runnervm0kj6c:11312] [11] plumed(+0x15365)[0x560889d54365]
[runnervm0kj6c:11312] *** End of error message ***
</pre>
{% endraw %}

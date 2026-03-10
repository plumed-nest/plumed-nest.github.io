**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervm0kj6c:11404] *** Process received signal ***
[runnervm0kj6c:11404] Signal: Aborted (6)
[runnervm0kj6c:11404] Signal code:  (-6)
[runnervm0kj6c:11404] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff9c6845330]
[runnervm0kj6c:11404] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff9c689eb2c]
[runnervm0kj6c:11404] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff9c684527e]
[runnervm0kj6c:11404] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff9c68288ff]
[runnervm0kj6c:11404] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff9c6ca5ff5]
[runnervm0kj6c:11404] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff9c6cbb0da]
[runnervm0kj6c:11404] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff9c6ca5a55]
[runnervm0kj6c:11404] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff9c6ca5a6f]
[runnervm0kj6c:11404] [ 8] plumed_master(+0x146dd)[0x55df6307b6dd]
[runnervm0kj6c:11404] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff9c682a1ca]
[runnervm0kj6c:11404] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff9c682a28b]
[runnervm0kj6c:11404] [11] plumed_master(+0x15365)[0x55df6307c365]
[runnervm0kj6c:11404] *** End of error message ***
</pre>
{% endraw %}

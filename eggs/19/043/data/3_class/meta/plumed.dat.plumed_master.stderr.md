**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervm0kj6c:11298] *** Process received signal ***
[runnervm0kj6c:11298] Signal: Aborted (6)
[runnervm0kj6c:11298] Signal code:  (-6)
[runnervm0kj6c:11298] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc071245330]
[runnervm0kj6c:11298] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc07129eb2c]
[runnervm0kj6c:11298] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc07124527e]
[runnervm0kj6c:11298] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc0712288ff]
[runnervm0kj6c:11298] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0716a5ff5]
[runnervm0kj6c:11298] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0716bb0da]
[runnervm0kj6c:11298] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0716a5a55]
[runnervm0kj6c:11298] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0716a5a6f]
[runnervm0kj6c:11298] [ 8] plumed_master(+0x146dd)[0x563d685956dd]
[runnervm0kj6c:11298] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc07122a1ca]
[runnervm0kj6c:11298] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc07122a28b]
[runnervm0kj6c:11298] [11] plumed_master(+0x15365)[0x563d68596365]
[runnervm0kj6c:11298] *** End of error message ***
</pre>
{% endraw %}

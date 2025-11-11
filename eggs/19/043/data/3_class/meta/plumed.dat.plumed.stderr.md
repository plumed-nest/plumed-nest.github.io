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
[runnervmw9dnm:12069] *** Process received signal ***
[runnervmw9dnm:12069] Signal: Aborted (6)
[runnervmw9dnm:12069] Signal code:  (-6)
[runnervmw9dnm:12069] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd1a6645330]
[runnervmw9dnm:12069] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd1a669eb2c]
[runnervmw9dnm:12069] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd1a664527e]
[runnervmw9dnm:12069] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd1a66288ff]
[runnervmw9dnm:12069] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1a6aa5ff5]
[runnervmw9dnm:12069] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1a6abb0da]
[runnervmw9dnm:12069] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1a6aa5a55]
[runnervmw9dnm:12069] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1a6aa5a6f]
[runnervmw9dnm:12069] [ 8] plumed(+0x146dd)[0x5620af1086dd]
[runnervmw9dnm:12069] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd1a662a1ca]
[runnervmw9dnm:12069] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd1a662a28b]
[runnervmw9dnm:12069] [11] plumed(+0x15365)[0x5620af109365]
[runnervmw9dnm:12069] *** End of error message ***
</pre>
{% endraw %}

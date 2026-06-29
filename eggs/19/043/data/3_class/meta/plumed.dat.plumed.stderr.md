**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmmklqx:11032] *** Process received signal ***
[runnervmmklqx:11032] Signal: Aborted (6)
[runnervmmklqx:11032] Signal code:  (-6)
[runnervmmklqx:11032] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe47ec45330]
[runnervmmklqx:11032] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe47ec9eb2c]
[runnervmmklqx:11032] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe47ec4527e]
[runnervmmklqx:11032] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe47ec288ff]
[runnervmmklqx:11032] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe47f0a5ff5]
[runnervmmklqx:11032] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe47f0bb0da]
[runnervmmklqx:11032] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe47f0a5a55]
[runnervmmklqx:11032] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe47f0a5a6f]
[runnervmmklqx:11032] [ 8] plumed(+0x146dd)[0x55f1f8e686dd]
[runnervmmklqx:11032] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe47ec2a1ca]
[runnervmmklqx:11032] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe47ec2a28b]
[runnervmmklqx:11032] [11] plumed(+0x15365)[0x55f1f8e69365]
[runnervmmklqx:11032] *** End of error message ***
</pre>
{% endraw %}

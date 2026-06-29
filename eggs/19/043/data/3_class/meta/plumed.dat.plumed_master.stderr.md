**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmmklqx:11048] *** Process received signal ***
[runnervmmklqx:11048] Signal: Aborted (6)
[runnervmmklqx:11048] Signal code:  (-6)
[runnervmmklqx:11048] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6eb8e45330]
[runnervmmklqx:11048] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6eb8e9eb2c]
[runnervmmklqx:11048] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6eb8e4527e]
[runnervmmklqx:11048] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6eb8e288ff]
[runnervmmklqx:11048] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6eb92a5ff5]
[runnervmmklqx:11048] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6eb92bb0da]
[runnervmmklqx:11048] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6eb92a5a55]
[runnervmmklqx:11048] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6eb92a5a6f]
[runnervmmklqx:11048] [ 8] plumed_master(+0x146dd)[0x55ae85e3e6dd]
[runnervmmklqx:11048] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6eb8e2a1ca]
[runnervmmklqx:11048] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6eb8e2a28b]
[runnervmmklqx:11048] [11] plumed_master(+0x15365)[0x55ae85e3f365]
[runnervmmklqx:11048] *** End of error message ***
</pre>
{% endraw %}

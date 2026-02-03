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
[runnervmkj6or:12275] *** Process received signal ***
[runnervmkj6or:12275] Signal: Aborted (6)
[runnervmkj6or:12275] Signal code:  (-6)
[runnervmkj6or:12275] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f558f445330]
[runnervmkj6or:12275] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f558f49eb2c]
[runnervmkj6or:12275] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f558f44527e]
[runnervmkj6or:12275] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f558f4288ff]
[runnervmkj6or:12275] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f558f8a5ff5]
[runnervmkj6or:12275] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f558f8bb0da]
[runnervmkj6or:12275] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f558f8a5a55]
[runnervmkj6or:12275] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f558f8a5a6f]
[runnervmkj6or:12275] [ 8] plumed_master(+0x146dd)[0x55846e30b6dd]
[runnervmkj6or:12275] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f558f42a1ca]
[runnervmkj6or:12275] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f558f42a28b]
[runnervmkj6or:12275] [11] plumed_master(+0x15365)[0x55846e30c365]
[runnervmkj6or:12275] *** End of error message ***
</pre>
{% endraw %}

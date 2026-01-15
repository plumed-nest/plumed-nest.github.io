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
[runnervmmtnos:39968] *** Process received signal ***
[runnervmmtnos:39968] Signal: Aborted (6)
[runnervmmtnos:39968] Signal code:  (-6)
[runnervmmtnos:39968] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f41f7445330]
[runnervmmtnos:39968] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f41f749eb2c]
[runnervmmtnos:39968] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f41f744527e]
[runnervmmtnos:39968] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41f74288ff]
[runnervmmtnos:39968] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41f78a5ff5]
[runnervmmtnos:39968] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41f78bb0da]
[runnervmmtnos:39968] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41f78a5a55]
[runnervmmtnos:39968] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41f78a5a6f]
[runnervmmtnos:39968] [ 8] plumed_master(+0x146dd)[0x55f2dfd3a6dd]
[runnervmmtnos:39968] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f41f742a1ca]
[runnervmmtnos:39968] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f41f742a28b]
[runnervmmtnos:39968] [11] plumed_master(+0x15365)[0x55f2dfd3b365]
[runnervmmtnos:39968] *** End of error message ***
</pre>
{% endraw %}

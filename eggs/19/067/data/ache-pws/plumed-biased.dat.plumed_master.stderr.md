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
[runnervmi13qx:40471] *** Process received signal ***
[runnervmi13qx:40471] Signal: Aborted (6)
[runnervmi13qx:40471] Signal code:  (-6)
[runnervmi13qx:40471] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f16f2445330]
[runnervmi13qx:40471] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f16f249eb2c]
[runnervmi13qx:40471] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f16f244527e]
[runnervmi13qx:40471] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f16f24288ff]
[runnervmi13qx:40471] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f16f28a5ff5]
[runnervmi13qx:40471] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f16f28bb0da]
[runnervmi13qx:40471] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f16f28a5a55]
[runnervmi13qx:40471] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f16f28a5a6f]
[runnervmi13qx:40471] [ 8] plumed_master(+0x146dd)[0x55c3fdaaa6dd]
[runnervmi13qx:40471] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f16f242a1ca]
[runnervmi13qx:40471] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f16f242a28b]
[runnervmi13qx:40471] [11] plumed_master(+0x15365)[0x55c3fdaab365]
[runnervmi13qx:40471] *** End of error message ***
</pre>
{% endraw %}

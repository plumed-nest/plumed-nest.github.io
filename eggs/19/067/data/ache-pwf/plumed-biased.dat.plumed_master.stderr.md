**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmi13qx:40395] *** Process received signal ***
[runnervmi13qx:40395] Signal: Aborted (6)
[runnervmi13qx:40395] Signal code:  (-6)
[runnervmi13qx:40395] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fce0c645330]
[runnervmi13qx:40395] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fce0c69eb2c]
[runnervmi13qx:40395] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fce0c64527e]
[runnervmi13qx:40395] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fce0c6288ff]
[runnervmi13qx:40395] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fce0caa5ff5]
[runnervmi13qx:40395] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fce0cabb0da]
[runnervmi13qx:40395] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fce0caa5a55]
[runnervmi13qx:40395] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fce0caa5a6f]
[runnervmi13qx:40395] [ 8] plumed_master(+0x146dd)[0x55625ded36dd]
[runnervmi13qx:40395] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fce0c62a1ca]
[runnervmi13qx:40395] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fce0c62a28b]
[runnervmi13qx:40395] [11] plumed_master(+0x15365)[0x55625ded4365]
[runnervmi13qx:40395] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmi13qx:40455] *** Process received signal ***
[runnervmi13qx:40455] Signal: Aborted (6)
[runnervmi13qx:40455] Signal code:  (-6)
[runnervmi13qx:40455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f653f245330]
[runnervmi13qx:40455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f653f29eb2c]
[runnervmi13qx:40455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f653f24527e]
[runnervmi13qx:40455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f653f2288ff]
[runnervmi13qx:40455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f653f6a5ff5]
[runnervmi13qx:40455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f653f6bb0da]
[runnervmi13qx:40455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f653f6a5a55]
[runnervmi13qx:40455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f653f6a5a6f]
[runnervmi13qx:40455] [ 8] plumed(+0x146dd)[0x55eaccd796dd]
[runnervmi13qx:40455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f653f22a1ca]
[runnervmi13qx:40455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f653f22a28b]
[runnervmi13qx:40455] [11] plumed(+0x15365)[0x55eaccd7a365]
[runnervmi13qx:40455] *** End of error message ***
</pre>
{% endraw %}

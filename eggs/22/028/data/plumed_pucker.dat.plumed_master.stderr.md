**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervmmklqx:08380] *** Process received signal ***
[runnervmmklqx:08380] Signal: Aborted (6)
[runnervmmklqx:08380] Signal code:  (-6)
[runnervmmklqx:08380] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3cc5c45330]
[runnervmmklqx:08380] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3cc5c9eb2c]
[runnervmmklqx:08380] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3cc5c4527e]
[runnervmmklqx:08380] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3cc5c288ff]
[runnervmmklqx:08380] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3cc60a5ff5]
[runnervmmklqx:08380] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3cc60bb0da]
[runnervmmklqx:08380] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3cc60a5a55]
[runnervmmklqx:08380] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3cc60a5a6f]
[runnervmmklqx:08380] [ 8] plumed_master(+0x146dd)[0x5592c9eac6dd]
[runnervmmklqx:08380] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3cc5c2a1ca]
[runnervmmklqx:08380] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3cc5c2a28b]
[runnervmmklqx:08380] [11] plumed_master(+0x15365)[0x5592c9ead365]
[runnervmmklqx:08380] *** End of error message ***
</pre>
{% endraw %}

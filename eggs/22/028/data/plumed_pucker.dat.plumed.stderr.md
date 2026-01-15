**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervmi13qx:34138] *** Process received signal ***
[runnervmi13qx:34138] Signal: Aborted (6)
[runnervmi13qx:34138] Signal code:  (-6)
[runnervmi13qx:34138] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa7b445330]
[runnervmi13qx:34138] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa7b49eb2c]
[runnervmi13qx:34138] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa7b44527e]
[runnervmi13qx:34138] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa7b4288ff]
[runnervmi13qx:34138] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa7b8a5ff5]
[runnervmi13qx:34138] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa7b8bb0da]
[runnervmi13qx:34138] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa7b8a5a55]
[runnervmi13qx:34138] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa7b8a5a6f]
[runnervmi13qx:34138] [ 8] plumed(+0x146dd)[0x55e0b92316dd]
[runnervmi13qx:34138] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa7b42a1ca]
[runnervmi13qx:34138] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa7b42a28b]
[runnervmi13qx:34138] [11] plumed(+0x15365)[0x55e0b9232365]
[runnervmi13qx:34138] *** End of error message ***
</pre>
{% endraw %}

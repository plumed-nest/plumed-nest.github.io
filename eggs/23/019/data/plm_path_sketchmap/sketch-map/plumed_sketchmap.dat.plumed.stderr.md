**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[runnervmkj6or:06611] *** Process received signal ***
[runnervmkj6or:06611] Signal: Aborted (6)
[runnervmkj6or:06611] Signal code:  (-6)
[runnervmkj6or:06611] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7edf245330]
[runnervmkj6or:06611] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7edf29eb2c]
[runnervmkj6or:06611] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7edf24527e]
[runnervmkj6or:06611] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7edf2288ff]
[runnervmkj6or:06611] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7edf6a5ff5]
[runnervmkj6or:06611] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7edf6bb0da]
[runnervmkj6or:06611] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7edf6a5a55]
[runnervmkj6or:06611] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7edf6a5a6f]
[runnervmkj6or:06611] [ 8] plumed(+0x146dd)[0x560130cf16dd]
[runnervmkj6or:06611] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7edf22a1ca]
[runnervmkj6or:06611] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7edf22a28b]
[runnervmkj6or:06611] [11] plumed(+0x15365)[0x560130cf2365]
[runnervmkj6or:06611] *** End of error message ***
</pre>
{% endraw %}

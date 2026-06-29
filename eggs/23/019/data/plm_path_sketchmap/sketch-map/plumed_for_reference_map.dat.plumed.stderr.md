**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[runnervmmklqx:06068] *** Process received signal ***
[runnervmmklqx:06068] Signal: Aborted (6)
[runnervmmklqx:06068] Signal code:  (-6)
[runnervmmklqx:06068] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1a5e445330]
[runnervmmklqx:06068] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1a5e49eb2c]
[runnervmmklqx:06068] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1a5e44527e]
[runnervmmklqx:06068] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1a5e4288ff]
[runnervmmklqx:06068] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1a5e8a5ff5]
[runnervmmklqx:06068] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1a5e8bb0da]
[runnervmmklqx:06068] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1a5e8a5a55]
[runnervmmklqx:06068] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1a5e8a5a6f]
[runnervmmklqx:06068] [ 8] plumed(+0x146dd)[0x55e43eee86dd]
[runnervmmklqx:06068] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1a5e42a1ca]
[runnervmmklqx:06068] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1a5e42a28b]
[runnervmmklqx:06068] [11] plumed(+0x15365)[0x55e43eee9365]
[runnervmmklqx:06068] *** End of error message ***
</pre>
{% endraw %}

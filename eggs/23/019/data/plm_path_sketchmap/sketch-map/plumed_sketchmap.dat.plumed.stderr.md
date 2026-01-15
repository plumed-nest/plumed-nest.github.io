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
[runnervmmtnos:33354] *** Process received signal ***
[runnervmmtnos:33354] Signal: Aborted (6)
[runnervmmtnos:33354] Signal code:  (-6)
[runnervmmtnos:33354] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2ad6e45330]
[runnervmmtnos:33354] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2ad6e9eb2c]
[runnervmmtnos:33354] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2ad6e4527e]
[runnervmmtnos:33354] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2ad6e288ff]
[runnervmmtnos:33354] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2ad72a5ff5]
[runnervmmtnos:33354] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2ad72bb0da]
[runnervmmtnos:33354] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2ad72a5a55]
[runnervmmtnos:33354] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2ad72a5a6f]
[runnervmmtnos:33354] [ 8] plumed(+0x146dd)[0x55c329d976dd]
[runnervmmtnos:33354] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2ad6e2a1ca]
[runnervmmtnos:33354] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2ad6e2a28b]
[runnervmmtnos:33354] [11] plumed(+0x15365)[0x55c329d98365]
[runnervmmtnos:33354] *** End of error message ***
</pre>
{% endraw %}

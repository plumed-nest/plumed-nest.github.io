**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[runnervmkj6or:06531] *** Process received signal ***
[runnervmkj6or:06531] Signal: Aborted (6)
[runnervmkj6or:06531] Signal code:  (-6)
[runnervmkj6or:06531] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fee62e45330]
[runnervmkj6or:06531] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fee62e9eb2c]
[runnervmkj6or:06531] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fee62e4527e]
[runnervmkj6or:06531] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fee62e288ff]
[runnervmkj6or:06531] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fee632a5ff5]
[runnervmkj6or:06531] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fee632bb0da]
[runnervmkj6or:06531] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fee632a5a55]
[runnervmkj6or:06531] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fee632a5a6f]
[runnervmkj6or:06531] [ 8] plumed(+0x146dd)[0x560ac54f76dd]
[runnervmkj6or:06531] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fee62e2a1ca]
[runnervmkj6or:06531] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fee62e2a28b]
[runnervmkj6or:06531] [11] plumed(+0x15365)[0x560ac54f8365]
[runnervmkj6or:06531] *** End of error message ***
</pre>
{% endraw %}

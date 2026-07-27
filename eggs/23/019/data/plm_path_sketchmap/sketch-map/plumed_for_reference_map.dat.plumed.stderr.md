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
[runnervmvrwv9:07823] *** Process received signal ***
[runnervmvrwv9:07823] Signal: Aborted (6)
[runnervmvrwv9:07823] Signal code:  (-6)
[runnervmvrwv9:07823] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec39245330]
[runnervmvrwv9:07823] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec3929eb2c]
[runnervmvrwv9:07823] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec3924527e]
[runnervmvrwv9:07823] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec392288ff]
[runnervmvrwv9:07823] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec396a5ff5]
[runnervmvrwv9:07823] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec396bb0da]
[runnervmvrwv9:07823] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec396a5a55]
[runnervmvrwv9:07823] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec396a5a6f]
[runnervmvrwv9:07823] [ 8] plumed(+0x146dd)[0x56400dd086dd]
[runnervmvrwv9:07823] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec3922a1ca]
[runnervmvrwv9:07823] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec3922a28b]
[runnervmvrwv9:07823] [11] plumed(+0x15365)[0x56400dd09365]
[runnervmvrwv9:07823] *** End of error message ***
</pre>
{% endraw %}

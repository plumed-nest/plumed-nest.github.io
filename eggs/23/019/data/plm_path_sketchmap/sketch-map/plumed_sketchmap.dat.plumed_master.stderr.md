**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[runnervmeorf1:06501] *** Process received signal ***
[runnervmeorf1:06501] Signal: Aborted (6)
[runnervmeorf1:06501] Signal code:  (-6)
[runnervmeorf1:06501] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5efa445330]
[runnervmeorf1:06501] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5efa49eb2c]
[runnervmeorf1:06501] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5efa44527e]
[runnervmeorf1:06501] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5efa4288ff]
[runnervmeorf1:06501] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5efa8a5ff5]
[runnervmeorf1:06501] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5efa8bb0da]
[runnervmeorf1:06501] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5efa8a5a55]
[runnervmeorf1:06501] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5efa8a5a6f]
[runnervmeorf1:06501] [ 8] plumed_master(+0x146dd)[0x55e33e0406dd]
[runnervmeorf1:06501] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5efa42a1ca]
[runnervmeorf1:06501] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5efa42a28b]
[runnervmeorf1:06501] [11] plumed_master(+0x15365)[0x55e33e041365]
[runnervmeorf1:06501] *** End of error message ***
</pre>
{% endraw %}

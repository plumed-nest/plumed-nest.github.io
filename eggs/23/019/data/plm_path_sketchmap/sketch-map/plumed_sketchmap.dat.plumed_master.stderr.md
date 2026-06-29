**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[runnervmmklqx:06161] *** Process received signal ***
[runnervmmklqx:06161] Signal: Aborted (6)
[runnervmmklqx:06161] Signal code:  (-6)
[runnervmmklqx:06161] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa7a8445330]
[runnervmmklqx:06161] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa7a849eb2c]
[runnervmmklqx:06161] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa7a844527e]
[runnervmmklqx:06161] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa7a84288ff]
[runnervmmklqx:06161] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa7a88a5ff5]
[runnervmmklqx:06161] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa7a88bb0da]
[runnervmmklqx:06161] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa7a88a5a55]
[runnervmmklqx:06161] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa7a88a5a6f]
[runnervmmklqx:06161] [ 8] plumed_master(+0x146dd)[0x559941b226dd]
[runnervmmklqx:06161] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa7a842a1ca]
[runnervmmklqx:06161] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa7a842a28b]
[runnervmmklqx:06161] [11] plumed_master(+0x15365)[0x559941b23365]
[runnervmmklqx:06161] *** End of error message ***
</pre>
{% endraw %}

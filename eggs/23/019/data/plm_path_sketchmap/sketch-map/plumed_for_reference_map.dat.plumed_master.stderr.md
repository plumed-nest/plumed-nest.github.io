**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[runnervmmklqx:06084] *** Process received signal ***
[runnervmmklqx:06084] Signal: Aborted (6)
[runnervmmklqx:06084] Signal code:  (-6)
[runnervmmklqx:06084] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa572c45330]
[runnervmmklqx:06084] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa572c9eb2c]
[runnervmmklqx:06084] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa572c4527e]
[runnervmmklqx:06084] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa572c288ff]
[runnervmmklqx:06084] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa5730a5ff5]
[runnervmmklqx:06084] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa5730bb0da]
[runnervmmklqx:06084] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa5730a5a55]
[runnervmmklqx:06084] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa5730a5a6f]
[runnervmmklqx:06084] [ 8] plumed_master(+0x146dd)[0x56219a7896dd]
[runnervmmklqx:06084] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa572c2a1ca]
[runnervmmklqx:06084] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa572c2a28b]
[runnervmmklqx:06084] [11] plumed_master(+0x15365)[0x56219a78a365]
[runnervmmklqx:06084] *** End of error message ***
</pre>
{% endraw %}

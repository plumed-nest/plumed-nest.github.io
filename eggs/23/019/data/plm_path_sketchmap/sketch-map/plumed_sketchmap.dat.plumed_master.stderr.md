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
[runnervmkj6or:06627] *** Process received signal ***
[runnervmkj6or:06627] Signal: Aborted (6)
[runnervmkj6or:06627] Signal code:  (-6)
[runnervmkj6or:06627] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5530845330]
[runnervmkj6or:06627] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f553089eb2c]
[runnervmkj6or:06627] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f553084527e]
[runnervmkj6or:06627] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55308288ff]
[runnervmkj6or:06627] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5530ca5ff5]
[runnervmkj6or:06627] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5530cbb0da]
[runnervmkj6or:06627] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5530ca5a55]
[runnervmkj6or:06627] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5530ca5a6f]
[runnervmkj6or:06627] [ 8] plumed_master(+0x146dd)[0x55b9e142e6dd]
[runnervmkj6or:06627] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f553082a1ca]
[runnervmkj6or:06627] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f553082a28b]
[runnervmkj6or:06627] [11] plumed_master(+0x15365)[0x55b9e142f365]
[runnervmkj6or:06627] *** End of error message ***
</pre>
{% endraw %}

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
[runnervm0kj6c:06422] *** Process received signal ***
[runnervm0kj6c:06422] Signal: Aborted (6)
[runnervm0kj6c:06422] Signal code:  (-6)
[runnervm0kj6c:06422] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d1ea45330]
[runnervm0kj6c:06422] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d1ea9eb2c]
[runnervm0kj6c:06422] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d1ea4527e]
[runnervm0kj6c:06422] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d1ea288ff]
[runnervm0kj6c:06422] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d1eea5ff5]
[runnervm0kj6c:06422] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d1eebb0da]
[runnervm0kj6c:06422] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d1eea5a55]
[runnervm0kj6c:06422] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d1eea5a6f]
[runnervm0kj6c:06422] [ 8] plumed_master(+0x146dd)[0x557d78e686dd]
[runnervm0kj6c:06422] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d1ea2a1ca]
[runnervm0kj6c:06422] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d1ea2a28b]
[runnervm0kj6c:06422] [11] plumed_master(+0x15365)[0x557d78e69365]
[runnervm0kj6c:06422] *** End of error message ***
</pre>
{% endraw %}

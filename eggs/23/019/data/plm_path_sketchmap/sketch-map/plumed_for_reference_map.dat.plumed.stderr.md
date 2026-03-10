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
[runnervm0kj6c:06330] *** Process received signal ***
[runnervm0kj6c:06330] Signal: Aborted (6)
[runnervm0kj6c:06330] Signal code:  (-6)
[runnervm0kj6c:06330] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9918c45330]
[runnervm0kj6c:06330] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9918c9eb2c]
[runnervm0kj6c:06330] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9918c4527e]
[runnervm0kj6c:06330] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9918c288ff]
[runnervm0kj6c:06330] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99190a5ff5]
[runnervm0kj6c:06330] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99190bb0da]
[runnervm0kj6c:06330] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99190a5a55]
[runnervm0kj6c:06330] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99190a5a6f]
[runnervm0kj6c:06330] [ 8] plumed(+0x146dd)[0x562c4a4906dd]
[runnervm0kj6c:06330] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9918c2a1ca]
[runnervm0kj6c:06330] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9918c2a28b]
[runnervm0kj6c:06330] [11] plumed(+0x15365)[0x562c4a491365]
[runnervm0kj6c:06330] *** End of error message ***
</pre>
{% endraw %}

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
[runnervm0kj6c:06407] *** Process received signal ***
[runnervm0kj6c:06407] Signal: Aborted (6)
[runnervm0kj6c:06407] Signal code:  (-6)
[runnervm0kj6c:06407] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff2ad445330]
[runnervm0kj6c:06407] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff2ad49eb2c]
[runnervm0kj6c:06407] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff2ad44527e]
[runnervm0kj6c:06407] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2ad4288ff]
[runnervm0kj6c:06407] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2ad8a5ff5]
[runnervm0kj6c:06407] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2ad8bb0da]
[runnervm0kj6c:06407] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2ad8a5a55]
[runnervm0kj6c:06407] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2ad8a5a6f]
[runnervm0kj6c:06407] [ 8] plumed(+0x146dd)[0x562625cdc6dd]
[runnervm0kj6c:06407] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff2ad42a1ca]
[runnervm0kj6c:06407] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff2ad42a28b]
[runnervm0kj6c:06407] [11] plumed(+0x15365)[0x562625cdd365]
[runnervm0kj6c:06407] *** End of error message ***
</pre>
{% endraw %}

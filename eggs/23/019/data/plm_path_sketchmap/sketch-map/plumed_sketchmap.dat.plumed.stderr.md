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
[fv-az1701-508:62554] *** Process received signal ***
[fv-az1701-508:62554] Signal: Aborted (6)
[fv-az1701-508:62554] Signal code:  (-6)
[fv-az1701-508:62554] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f25fb245330]
[fv-az1701-508:62554] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f25fb29eb2c]
[fv-az1701-508:62554] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f25fb24527e]
[fv-az1701-508:62554] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f25fb2288ff]
[fv-az1701-508:62554] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f25fb6a5ff5]
[fv-az1701-508:62554] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f25fb6bb0da]
[fv-az1701-508:62554] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f25fb6a5a55]
[fv-az1701-508:62554] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f25fb6a5a6f]
[fv-az1701-508:62554] [ 8] plumed(+0x146dd)[0x55eafd30d6dd]
[fv-az1701-508:62554] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f25fb22a1ca]
[fv-az1701-508:62554] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f25fb22a28b]
[fv-az1701-508:62554] [11] plumed(+0x15365)[0x55eafd30e365]
[fv-az1701-508:62554] *** End of error message ***
</pre>
{% endraw %}

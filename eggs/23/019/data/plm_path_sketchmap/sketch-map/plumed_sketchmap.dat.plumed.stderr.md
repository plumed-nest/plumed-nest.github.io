**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[runnervmmklqx:06145] *** Process received signal ***
[runnervmmklqx:06145] Signal: Aborted (6)
[runnervmmklqx:06145] Signal code:  (-6)
[runnervmmklqx:06145] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b27445330]
[runnervmmklqx:06145] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b2749eb2c]
[runnervmmklqx:06145] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b2744527e]
[runnervmmklqx:06145] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b274288ff]
[runnervmmklqx:06145] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b278a5ff5]
[runnervmmklqx:06145] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b278bb0da]
[runnervmmklqx:06145] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b278a5a55]
[runnervmmklqx:06145] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b278a5a6f]
[runnervmmklqx:06145] [ 8] plumed(+0x146dd)[0x55a2a474e6dd]
[runnervmmklqx:06145] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b2742a1ca]
[runnervmmklqx:06145] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b2742a28b]
[runnervmmklqx:06145] [11] plumed(+0x15365)[0x55a2a474f365]
[runnervmmklqx:06145] *** End of error message ***
</pre>
{% endraw %}

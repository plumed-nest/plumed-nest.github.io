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
[runnervmw9dnm:07961] *** Process received signal ***
[runnervmw9dnm:07961] Signal: Aborted (6)
[runnervmw9dnm:07961] Signal code:  (-6)
[runnervmw9dnm:07961] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6e5ae45330]
[runnervmw9dnm:07961] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6e5ae9eb2c]
[runnervmw9dnm:07961] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6e5ae4527e]
[runnervmw9dnm:07961] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6e5ae288ff]
[runnervmw9dnm:07961] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6e5b2a5ff5]
[runnervmw9dnm:07961] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6e5b2bb0da]
[runnervmw9dnm:07961] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6e5b2a5a55]
[runnervmw9dnm:07961] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6e5b2a5a6f]
[runnervmw9dnm:07961] [ 8] plumed(+0x146dd)[0x55a995e2b6dd]
[runnervmw9dnm:07961] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6e5ae2a1ca]
[runnervmw9dnm:07961] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6e5ae2a28b]
[runnervmw9dnm:07961] [11] plumed(+0x15365)[0x55a995e2c365]
[runnervmw9dnm:07961] *** End of error message ***
</pre>
{% endraw %}

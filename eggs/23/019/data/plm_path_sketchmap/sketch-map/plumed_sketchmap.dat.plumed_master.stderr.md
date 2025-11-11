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
[runnervmw9dnm:08054] *** Process received signal ***
[runnervmw9dnm:08054] Signal: Aborted (6)
[runnervmw9dnm:08054] Signal code:  (-6)
[runnervmw9dnm:08054] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff1dbc45330]
[runnervmw9dnm:08054] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff1dbc9eb2c]
[runnervmw9dnm:08054] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff1dbc4527e]
[runnervmw9dnm:08054] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1dbc288ff]
[runnervmw9dnm:08054] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1dc0a5ff5]
[runnervmw9dnm:08054] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1dc0bb0da]
[runnervmw9dnm:08054] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1dc0a5a55]
[runnervmw9dnm:08054] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1dc0a5a6f]
[runnervmw9dnm:08054] [ 8] plumed_master(+0x146dd)[0x55dc3280b6dd]
[runnervmw9dnm:08054] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff1dbc2a1ca]
[runnervmw9dnm:08054] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff1dbc2a28b]
[runnervmw9dnm:08054] [11] plumed_master(+0x15365)[0x55dc3280c365]
[runnervmw9dnm:08054] *** End of error message ***
</pre>
{% endraw %}

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
[runnervmvrwv9:07900] *** Process received signal ***
[runnervmvrwv9:07900] Signal: Aborted (6)
[runnervmvrwv9:07900] Signal code:  (-6)
[runnervmvrwv9:07900] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3bf7245330]
[runnervmvrwv9:07900] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3bf729eb2c]
[runnervmvrwv9:07900] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3bf724527e]
[runnervmvrwv9:07900] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3bf72288ff]
[runnervmvrwv9:07900] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3bf76a5ff5]
[runnervmvrwv9:07900] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3bf76bb0da]
[runnervmvrwv9:07900] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3bf76a5a55]
[runnervmvrwv9:07900] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3bf76a5a6f]
[runnervmvrwv9:07900] [ 8] plumed(+0x146dd)[0x55ff40a676dd]
[runnervmvrwv9:07900] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3bf722a1ca]
[runnervmvrwv9:07900] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3bf722a28b]
[runnervmvrwv9:07900] [11] plumed(+0x15365)[0x55ff40a68365]
[runnervmvrwv9:07900] *** End of error message ***
</pre>
{% endraw %}

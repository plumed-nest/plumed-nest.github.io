**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmvrwv9:05462] *** Process received signal ***
[runnervmvrwv9:05462] Signal: Aborted (6)
[runnervmvrwv9:05462] Signal code:  (-6)
[runnervmvrwv9:05462] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f898b045330]
[runnervmvrwv9:05462] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f898b09eb2c]
[runnervmvrwv9:05462] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f898b04527e]
[runnervmvrwv9:05462] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f898b0288ff]
[runnervmvrwv9:05462] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f898b4a5ff5]
[runnervmvrwv9:05462] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f898b4bb0da]
[runnervmvrwv9:05462] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f898b4a5a55]
[runnervmvrwv9:05462] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f898b4a5a6f]
[runnervmvrwv9:05462] [ 8] plumed_master(+0x146dd)[0x561987bbb6dd]
[runnervmvrwv9:05462] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f898b02a1ca]
[runnervmvrwv9:05462] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f898b02a28b]
[runnervmvrwv9:05462] [11] plumed_master(+0x15365)[0x561987bbc365]
[runnervmvrwv9:05462] *** End of error message ***
</pre>
{% endraw %}

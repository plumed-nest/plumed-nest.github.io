**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmmklqx:05693] *** Process received signal ***
[runnervmmklqx:05693] Signal: Aborted (6)
[runnervmmklqx:05693] Signal code:  (-6)
[runnervmmklqx:05693] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b09245330]
[runnervmmklqx:05693] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b0929eb2c]
[runnervmmklqx:05693] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b0924527e]
[runnervmmklqx:05693] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b092288ff]
[runnervmmklqx:05693] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b096a5ff5]
[runnervmmklqx:05693] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b096bb0da]
[runnervmmklqx:05693] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b096a5a55]
[runnervmmklqx:05693] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b096a5a6f]
[runnervmmklqx:05693] [ 8] plumed_master(+0x146dd)[0x55cb9ddc86dd]
[runnervmmklqx:05693] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b0922a1ca]
[runnervmmklqx:05693] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b0922a28b]
[runnervmmklqx:05693] [11] plumed_master(+0x15365)[0x55cb9ddc9365]
[runnervmmklqx:05693] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @38 : keyword ARG is compulsory for this action
[runnervmmklqx:05770] *** Process received signal ***
[runnervmmklqx:05770] Signal: Aborted (6)
[runnervmmklqx:05770] Signal code:  (-6)
[runnervmmklqx:05770] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0835e45330]
[runnervmmklqx:05770] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0835e9eb2c]
[runnervmmklqx:05770] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0835e4527e]
[runnervmmklqx:05770] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0835e288ff]
[runnervmmklqx:05770] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f08362a5ff5]
[runnervmmklqx:05770] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f08362bb0da]
[runnervmmklqx:05770] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f08362a5a55]
[runnervmmklqx:05770] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f08362a5a6f]
[runnervmmklqx:05770] [ 8] plumed_master(+0x146dd)[0x5587cea2f6dd]
[runnervmmklqx:05770] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0835e2a1ca]
[runnervmmklqx:05770] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0835e2a28b]
[runnervmmklqx:05770] [11] plumed_master(+0x15365)[0x5587cea30365]
[runnervmmklqx:05770] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  5dro/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmmklqx:05591] *** Process received signal ***
[runnervmmklqx:05591] Signal: Aborted (6)
[runnervmmklqx:05591] Signal code:  (-6)
[runnervmmklqx:05591] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd55fa45330]
[runnervmmklqx:05591] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd55fa9eb2c]
[runnervmmklqx:05591] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd55fa4527e]
[runnervmmklqx:05591] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd55fa288ff]
[runnervmmklqx:05591] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd55fea5ff5]
[runnervmmklqx:05591] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd55febb0da]
[runnervmmklqx:05591] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd55fea5a55]
[runnervmmklqx:05591] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd55fea5a6f]
[runnervmmklqx:05591] [ 8] plumed_master(+0x146dd)[0x563a14eef6dd]
[runnervmmklqx:05591] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd55fa2a1ca]
[runnervmmklqx:05591] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd55fa2a28b]
[runnervmmklqx:05591] [11] plumed_master(+0x15365)[0x563a14ef0365]
[runnervmmklqx:05591] *** End of error message ***
</pre>
{% endraw %}

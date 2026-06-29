**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmmklqx:05873] *** Process received signal ***
[runnervmmklqx:05873] Signal: Aborted (6)
[runnervmmklqx:05873] Signal code:  (-6)
[runnervmmklqx:05873] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f52dd045330]
[runnervmmklqx:05873] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f52dd09eb2c]
[runnervmmklqx:05873] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f52dd04527e]
[runnervmmklqx:05873] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f52dd0288ff]
[runnervmmklqx:05873] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f52dd4a5ff5]
[runnervmmklqx:05873] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f52dd4bb0da]
[runnervmmklqx:05873] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f52dd4a5a55]
[runnervmmklqx:05873] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f52dd4a5a6f]
[runnervmmklqx:05873] [ 8] plumed_master(+0x146dd)[0x55b2a7cb06dd]
[runnervmmklqx:05873] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f52dd02a1ca]
[runnervmmklqx:05873] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f52dd02a28b]
[runnervmmklqx:05873] [11] plumed_master(+0x15365)[0x55b2a7cb1365]
[runnervmmklqx:05873] *** End of error message ***
</pre>
{% endraw %}

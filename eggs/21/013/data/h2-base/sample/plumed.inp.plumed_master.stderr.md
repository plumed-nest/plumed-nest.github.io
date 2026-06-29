**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @18 : keyword ARG is compulsory for this action
[runnervmmklqx:09386] *** Process received signal ***
[runnervmmklqx:09386] Signal: Aborted (6)
[runnervmmklqx:09386] Signal code:  (-6)
[runnervmmklqx:09386] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0047a45330]
[runnervmmklqx:09386] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0047a9eb2c]
[runnervmmklqx:09386] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0047a4527e]
[runnervmmklqx:09386] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0047a288ff]
[runnervmmklqx:09386] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0047ea5ff5]
[runnervmmklqx:09386] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0047ebb0da]
[runnervmmklqx:09386] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0047ea5a55]
[runnervmmklqx:09386] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0047ea5a6f]
[runnervmmklqx:09386] [ 8] plumed_master(+0x146dd)[0x55a1b51cd6dd]
[runnervmmklqx:09386] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0047a2a1ca]
[runnervmmklqx:09386] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0047a2a28b]
[runnervmmklqx:09386] [11] plumed_master(+0x15365)[0x55a1b51ce365]
[runnervmmklqx:09386] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @50 : keyword ARG is compulsory for this action
[runnervmmklqx:08747] *** Process received signal ***
[runnervmmklqx:08747] Signal: Aborted (6)
[runnervmmklqx:08747] Signal code:  (-6)
[runnervmmklqx:08747] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5d8845330]
[runnervmmklqx:08747] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5d889eb2c]
[runnervmmklqx:08747] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5d884527e]
[runnervmmklqx:08747] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5d88288ff]
[runnervmmklqx:08747] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5d8ca5ff5]
[runnervmmklqx:08747] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5d8cbb0da]
[runnervmmklqx:08747] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5d8ca5a55]
[runnervmmklqx:08747] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5d8ca5a6f]
[runnervmmklqx:08747] [ 8] plumed_master(+0x146dd)[0x5591c034d6dd]
[runnervmmklqx:08747] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5d882a1ca]
[runnervmmklqx:08747] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5d882a28b]
[runnervmmklqx:08747] [11] plumed_master(+0x15365)[0x5591c034e365]
[runnervmmklqx:08747] *** End of error message ***
</pre>
{% endraw %}

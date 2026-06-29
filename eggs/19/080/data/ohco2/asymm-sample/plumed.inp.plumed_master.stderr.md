**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmmklqx:09957] *** Process received signal ***
[runnervmmklqx:09957] Signal: Aborted (6)
[runnervmmklqx:09957] Signal code:  (-6)
[runnervmmklqx:09957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d13e45330]
[runnervmmklqx:09957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d13e9eb2c]
[runnervmmklqx:09957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d13e4527e]
[runnervmmklqx:09957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d13e288ff]
[runnervmmklqx:09957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d142a5ff5]
[runnervmmklqx:09957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d142bb0da]
[runnervmmklqx:09957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d142a5a55]
[runnervmmklqx:09957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d142a5a6f]
[runnervmmklqx:09957] [ 8] plumed_master(+0x146dd)[0x55fcaafa06dd]
[runnervmmklqx:09957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d13e2a1ca]
[runnervmmklqx:09957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d13e2a28b]
[runnervmmklqx:09957] [11] plumed_master(+0x15365)[0x55fcaafa1365]
[runnervmmklqx:09957] *** End of error message ***
</pre>
{% endraw %}

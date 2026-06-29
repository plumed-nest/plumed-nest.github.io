**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmmklqx:10111] *** Process received signal ***
[runnervmmklqx:10111] Signal: Aborted (6)
[runnervmmklqx:10111] Signal code:  (-6)
[runnervmmklqx:10111] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7af3645330]
[runnervmmklqx:10111] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7af369eb2c]
[runnervmmklqx:10111] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7af364527e]
[runnervmmklqx:10111] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7af36288ff]
[runnervmmklqx:10111] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7af3aa5ff5]
[runnervmmklqx:10111] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7af3abb0da]
[runnervmmklqx:10111] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7af3aa5a55]
[runnervmmklqx:10111] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7af3aa5a6f]
[runnervmmklqx:10111] [ 8] plumed_master(+0x146dd)[0x558b9a0626dd]
[runnervmmklqx:10111] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7af362a1ca]
[runnervmmklqx:10111] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7af362a28b]
[runnervmmklqx:10111] [11] plumed_master(+0x15365)[0x558b9a063365]
[runnervmmklqx:10111] *** End of error message ***
</pre>
{% endraw %}

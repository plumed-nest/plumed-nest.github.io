**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmkj6or:12538] *** Process received signal ***
[runnervmkj6or:12538] Signal: Aborted (6)
[runnervmkj6or:12538] Signal code:  (-6)
[runnervmkj6or:12538] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83fe645330]
[runnervmkj6or:12538] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83fe69eb2c]
[runnervmkj6or:12538] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83fe64527e]
[runnervmkj6or:12538] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83fe6288ff]
[runnervmkj6or:12538] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83feaa5ff5]
[runnervmkj6or:12538] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83feabb0da]
[runnervmkj6or:12538] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83feaa5a55]
[runnervmkj6or:12538] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83feaa5a6f]
[runnervmkj6or:12538] [ 8] plumed_master(+0x146dd)[0x55e520acc6dd]
[runnervmkj6or:12538] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83fe62a1ca]
[runnervmkj6or:12538] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83fe62a28b]
[runnervmkj6or:12538] [11] plumed_master(+0x15365)[0x55e520acd365]
[runnervmkj6or:12538] *** End of error message ***
</pre>
{% endraw %}

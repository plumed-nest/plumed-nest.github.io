**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmkj6or:10806] *** Process received signal ***
[runnervmkj6or:10806] Signal: Aborted (6)
[runnervmkj6or:10806] Signal code:  (-6)
[runnervmkj6or:10806] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f20ece45330]
[runnervmkj6or:10806] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f20ece9eb2c]
[runnervmkj6or:10806] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f20ece4527e]
[runnervmkj6or:10806] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f20ece288ff]
[runnervmkj6or:10806] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f20ed2a5ff5]
[runnervmkj6or:10806] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f20ed2bb0da]
[runnervmkj6or:10806] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f20ed2a5a55]
[runnervmkj6or:10806] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f20ed2a5a6f]
[runnervmkj6or:10806] [ 8] plumed_master(+0x146dd)[0x564ef91006dd]
[runnervmkj6or:10806] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f20ece2a1ca]
[runnervmkj6or:10806] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f20ece2a28b]
[runnervmkj6or:10806] [11] plumed_master(+0x15365)[0x564ef9101365]
[runnervmkj6or:10806] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmkj6or:05207] *** Process received signal ***
[runnervmkj6or:05207] Signal: Aborted (6)
[runnervmkj6or:05207] Signal code:  (-6)
[runnervmkj6or:05207] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1091445330]
[runnervmkj6or:05207] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f109149eb2c]
[runnervmkj6or:05207] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f109144527e]
[runnervmkj6or:05207] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10914288ff]
[runnervmkj6or:05207] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f10918a5ff5]
[runnervmkj6or:05207] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f10918bb0da]
[runnervmkj6or:05207] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f10918a5a55]
[runnervmkj6or:05207] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f10918a5a6f]
[runnervmkj6or:05207] [ 8] plumed_master(+0x146dd)[0x55c91d3736dd]
[runnervmkj6or:05207] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f109142a1ca]
[runnervmkj6or:05207] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f109142a28b]
[runnervmkj6or:05207] [11] plumed_master(+0x15365)[0x55c91d374365]
[runnervmkj6or:05207] *** End of error message ***
</pre>
{% endraw %}

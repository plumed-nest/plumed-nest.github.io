**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervmkj6or:11626] *** Process received signal ***
[runnervmkj6or:11626] Signal: Aborted (6)
[runnervmkj6or:11626] Signal code:  (-6)
[runnervmkj6or:11626] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f781c445330]
[runnervmkj6or:11626] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f781c49eb2c]
[runnervmkj6or:11626] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f781c44527e]
[runnervmkj6or:11626] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f781c4288ff]
[runnervmkj6or:11626] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f781c8a5ff5]
[runnervmkj6or:11626] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f781c8bb0da]
[runnervmkj6or:11626] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f781c8a5a55]
[runnervmkj6or:11626] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f781c8a5a6f]
[runnervmkj6or:11626] [ 8] plumed_master(+0x146dd)[0x5563e47986dd]
[runnervmkj6or:11626] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f781c42a1ca]
[runnervmkj6or:11626] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f781c42a28b]
[runnervmkj6or:11626] [11] plumed_master(+0x15365)[0x5563e4799365]
[runnervmkj6or:11626] *** End of error message ***
</pre>
{% endraw %}

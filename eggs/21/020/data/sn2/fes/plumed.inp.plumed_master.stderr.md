**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[runnervmkj6or:07345] *** Process received signal ***
[runnervmkj6or:07345] Signal: Aborted (6)
[runnervmkj6or:07345] Signal code:  (-6)
[runnervmkj6or:07345] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2b27445330]
[runnervmkj6or:07345] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2b2749eb2c]
[runnervmkj6or:07345] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2b2744527e]
[runnervmkj6or:07345] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2b274288ff]
[runnervmkj6or:07345] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2b278a5ff5]
[runnervmkj6or:07345] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2b278bb0da]
[runnervmkj6or:07345] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2b278a5a55]
[runnervmkj6or:07345] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2b278a5a6f]
[runnervmkj6or:07345] [ 8] plumed_master(+0x146dd)[0x55a0b98d26dd]
[runnervmkj6or:07345] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2b2742a1ca]
[runnervmkj6or:07345] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2b2742a28b]
[runnervmkj6or:07345] [11] plumed_master(+0x15365)[0x55a0b98d3365]
[runnervmkj6or:07345] *** End of error message ***
</pre>
{% endraw %}

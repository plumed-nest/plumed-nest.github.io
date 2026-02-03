**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmkj6or:10923] *** Process received signal ***
[runnervmkj6or:10923] Signal: Aborted (6)
[runnervmkj6or:10923] Signal code:  (-6)
[runnervmkj6or:10923] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f56c7845330]
[runnervmkj6or:10923] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f56c789eb2c]
[runnervmkj6or:10923] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f56c784527e]
[runnervmkj6or:10923] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56c78288ff]
[runnervmkj6or:10923] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f56c7ca5ff5]
[runnervmkj6or:10923] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f56c7cbb0da]
[runnervmkj6or:10923] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f56c7ca5a55]
[runnervmkj6or:10923] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f56c7ca5a6f]
[runnervmkj6or:10923] [ 8] plumed_master(+0x146dd)[0x5568cde376dd]
[runnervmkj6or:10923] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f56c782a1ca]
[runnervmkj6or:10923] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f56c782a28b]
[runnervmkj6or:10923] [11] plumed_master(+0x15365)[0x5568cde38365]
[runnervmkj6or:10923] *** End of error message ***
</pre>
{% endraw %}

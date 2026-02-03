**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @69 : keyword ARG is compulsory for this action
[runnervmkj6or:08361] *** Process received signal ***
[runnervmkj6or:08361] Signal: Aborted (6)
[runnervmkj6or:08361] Signal code:  (-6)
[runnervmkj6or:08361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa655045330]
[runnervmkj6or:08361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa65509eb2c]
[runnervmkj6or:08361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa65504527e]
[runnervmkj6or:08361] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa6550288ff]
[runnervmkj6or:08361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa6554a5ff5]
[runnervmkj6or:08361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa6554bb0da]
[runnervmkj6or:08361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa6554a5a55]
[runnervmkj6or:08361] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa6554a5a6f]
[runnervmkj6or:08361] [ 8] plumed_master(+0x146dd)[0x565452fc96dd]
[runnervmkj6or:08361] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa65502a1ca]
[runnervmkj6or:08361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa65502a28b]
[runnervmkj6or:08361] [11] plumed_master(+0x15365)[0x565452fca365]
[runnervmkj6or:08361] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmkj6or:06679] *** Process received signal ***
[runnervmkj6or:06679] Signal: Aborted (6)
[runnervmkj6or:06679] Signal code:  (-6)
[runnervmkj6or:06679] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd429a45330]
[runnervmkj6or:06679] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd429a9eb2c]
[runnervmkj6or:06679] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd429a4527e]
[runnervmkj6or:06679] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd429a288ff]
[runnervmkj6or:06679] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd429ea5ff5]
[runnervmkj6or:06679] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd429ebb0da]
[runnervmkj6or:06679] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd429ea5a55]
[runnervmkj6or:06679] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd429ea5a6f]
[runnervmkj6or:06679] [ 8] plumed_master(+0x146dd)[0x55ffa10946dd]
[runnervmkj6or:06679] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd429a2a1ca]
[runnervmkj6or:06679] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd429a2a28b]
[runnervmkj6or:06679] [11] plumed_master(+0x15365)[0x55ffa1095365]
[runnervmkj6or:06679] *** End of error message ***
</pre>
{% endraw %}

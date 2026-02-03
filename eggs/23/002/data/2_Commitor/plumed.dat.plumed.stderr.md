**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmkj6or:06560] *** Process received signal ***
[runnervmkj6or:06560] Signal: Aborted (6)
[runnervmkj6or:06560] Signal code:  (-6)
[runnervmkj6or:06560] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fddc2a45330]
[runnervmkj6or:06560] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fddc2a9eb2c]
[runnervmkj6or:06560] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fddc2a4527e]
[runnervmkj6or:06560] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fddc2a288ff]
[runnervmkj6or:06560] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fddc2ea5ff5]
[runnervmkj6or:06560] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fddc2ebb0da]
[runnervmkj6or:06560] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fddc2ea5a55]
[runnervmkj6or:06560] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fddc2ea5a6f]
[runnervmkj6or:06560] [ 8] plumed(+0x146dd)[0x55d605ec66dd]
[runnervmkj6or:06560] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fddc2a2a1ca]
[runnervmkj6or:06560] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fddc2a2a28b]
[runnervmkj6or:06560] [11] plumed(+0x15365)[0x55d605ec7365]
[runnervmkj6or:06560] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmkj6or:06663] *** Process received signal ***
[runnervmkj6or:06663] Signal: Aborted (6)
[runnervmkj6or:06663] Signal code:  (-6)
[runnervmkj6or:06663] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5fc6c45330]
[runnervmkj6or:06663] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5fc6c9eb2c]
[runnervmkj6or:06663] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5fc6c4527e]
[runnervmkj6or:06663] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5fc6c288ff]
[runnervmkj6or:06663] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5fc70a5ff5]
[runnervmkj6or:06663] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5fc70bb0da]
[runnervmkj6or:06663] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5fc70a5a55]
[runnervmkj6or:06663] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5fc70a5a6f]
[runnervmkj6or:06663] [ 8] plumed(+0x146dd)[0x55a1d85c96dd]
[runnervmkj6or:06663] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5fc6c2a1ca]
[runnervmkj6or:06663] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5fc6c2a28b]
[runnervmkj6or:06663] [11] plumed(+0x15365)[0x55a1d85ca365]
[runnervmkj6or:06663] *** End of error message ***
</pre>
{% endraw %}

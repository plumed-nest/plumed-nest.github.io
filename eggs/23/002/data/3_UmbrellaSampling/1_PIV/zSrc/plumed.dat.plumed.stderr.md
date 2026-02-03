**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmkj6or:06612] *** Process received signal ***
[runnervmkj6or:06612] Signal: Aborted (6)
[runnervmkj6or:06612] Signal code:  (-6)
[runnervmkj6or:06612] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f50f6445330]
[runnervmkj6or:06612] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f50f649eb2c]
[runnervmkj6or:06612] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f50f644527e]
[runnervmkj6or:06612] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f50f64288ff]
[runnervmkj6or:06612] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f50f68a5ff5]
[runnervmkj6or:06612] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f50f68bb0da]
[runnervmkj6or:06612] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f50f68a5a55]
[runnervmkj6or:06612] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f50f68a5a6f]
[runnervmkj6or:06612] [ 8] plumed(+0x146dd)[0x55ae88a296dd]
[runnervmkj6or:06612] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f50f642a1ca]
[runnervmkj6or:06612] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f50f642a28b]
[runnervmkj6or:06612] [11] plumed(+0x15365)[0x55ae88a2a365]
[runnervmkj6or:06612] *** End of error message ***
</pre>
{% endraw %}

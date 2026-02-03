**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[runnervmkj6or:04660] *** Process received signal ***
[runnervmkj6or:04660] Signal: Aborted (6)
[runnervmkj6or:04660] Signal code:  (-6)
[runnervmkj6or:04660] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdfb1245330]
[runnervmkj6or:04660] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdfb129eb2c]
[runnervmkj6or:04660] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdfb124527e]
[runnervmkj6or:04660] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdfb12288ff]
[runnervmkj6or:04660] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdfb16a5ff5]
[runnervmkj6or:04660] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdfb16bb0da]
[runnervmkj6or:04660] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdfb16a5a55]
[runnervmkj6or:04660] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdfb16a5a6f]
[runnervmkj6or:04660] [ 8] plumed_master(+0x146dd)[0x560b6f95f6dd]
[runnervmkj6or:04660] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdfb122a1ca]
[runnervmkj6or:04660] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdfb122a28b]
[runnervmkj6or:04660] [11] plumed_master(+0x15365)[0x560b6f960365]
[runnervmkj6or:04660] *** End of error message ***
</pre>
{% endraw %}

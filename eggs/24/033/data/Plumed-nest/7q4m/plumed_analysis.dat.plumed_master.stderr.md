**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @252 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[runnervmkj6or:04843] *** Process received signal ***
[runnervmkj6or:04843] Signal: Aborted (6)
[runnervmkj6or:04843] Signal code:  (-6)
[runnervmkj6or:04843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f824ac45330]
[runnervmkj6or:04843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f824ac9eb2c]
[runnervmkj6or:04843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f824ac4527e]
[runnervmkj6or:04843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f824ac288ff]
[runnervmkj6or:04843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f824b0a5ff5]
[runnervmkj6or:04843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f824b0bb0da]
[runnervmkj6or:04843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f824b0a5a55]
[runnervmkj6or:04843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f824b0a5a6f]
[runnervmkj6or:04843] [ 8] plumed_master(+0x146dd)[0x55a96698a6dd]
[runnervmkj6or:04843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f824ac2a1ca]
[runnervmkj6or:04843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f824ac2a28b]
[runnervmkj6or:04843] [11] plumed_master(+0x15365)[0x55a96698b365]
[runnervmkj6or:04843] *** End of error message ***
</pre>
{% endraw %}

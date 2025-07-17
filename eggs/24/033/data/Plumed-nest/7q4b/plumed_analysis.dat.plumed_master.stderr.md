**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[pkrvmq0rgcvqdmg:05780] *** Process received signal ***
[pkrvmq0rgcvqdmg:05780] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:05780] Signal code:  (-6)
[pkrvmq0rgcvqdmg:05780] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbbbca45330]
[pkrvmq0rgcvqdmg:05780] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbbbca9eb2c]
[pkrvmq0rgcvqdmg:05780] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbbbca4527e]
[pkrvmq0rgcvqdmg:05780] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbbbca288ff]
[pkrvmq0rgcvqdmg:05780] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbbbcea5ff5]
[pkrvmq0rgcvqdmg:05780] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbbbcebb0da]
[pkrvmq0rgcvqdmg:05780] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbbbcea5a55]
[pkrvmq0rgcvqdmg:05780] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbbbcea5a6f]
[pkrvmq0rgcvqdmg:05780] [ 8] plumed_master(+0x146dd)[0x55ab782b16dd]
[pkrvmq0rgcvqdmg:05780] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbbbca2a1ca]
[pkrvmq0rgcvqdmg:05780] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbbbca2a28b]
[pkrvmq0rgcvqdmg:05780] [11] plumed_master(+0x15365)[0x55ab782b2365]
[pkrvmq0rgcvqdmg:05780] *** End of error message ***
</pre>
{% endraw %}

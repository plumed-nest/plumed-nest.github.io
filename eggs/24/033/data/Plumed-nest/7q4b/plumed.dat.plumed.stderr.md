**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmq0rgcvqdmg:05719] *** Process received signal ***
[pkrvmq0rgcvqdmg:05719] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:05719] Signal code:  (-6)
[pkrvmq0rgcvqdmg:05719] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9707845330]
[pkrvmq0rgcvqdmg:05719] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f970789eb2c]
[pkrvmq0rgcvqdmg:05719] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f970784527e]
[pkrvmq0rgcvqdmg:05719] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97078288ff]
[pkrvmq0rgcvqdmg:05719] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9707ca5ff5]
[pkrvmq0rgcvqdmg:05719] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9707cbb0da]
[pkrvmq0rgcvqdmg:05719] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9707ca5a55]
[pkrvmq0rgcvqdmg:05719] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9707ca5a6f]
[pkrvmq0rgcvqdmg:05719] [ 8] plumed(+0x146dd)[0x555c51bf26dd]
[pkrvmq0rgcvqdmg:05719] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f970782a1ca]
[pkrvmq0rgcvqdmg:05719] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f970782a28b]
[pkrvmq0rgcvqdmg:05719] [11] plumed(+0x15365)[0x555c51bf3365]
[pkrvmq0rgcvqdmg:05719] *** End of error message ***
</pre>
{% endraw %}

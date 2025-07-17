**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmq0rgcvqdmg:05913] *** Process received signal ***
[pkrvmq0rgcvqdmg:05913] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:05913] Signal code:  (-6)
[pkrvmq0rgcvqdmg:05913] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe3ac45330]
[pkrvmq0rgcvqdmg:05913] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe3ac9eb2c]
[pkrvmq0rgcvqdmg:05913] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe3ac4527e]
[pkrvmq0rgcvqdmg:05913] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe3ac288ff]
[pkrvmq0rgcvqdmg:05913] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe3b0a5ff5]
[pkrvmq0rgcvqdmg:05913] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe3b0bb0da]
[pkrvmq0rgcvqdmg:05913] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe3b0a5a55]
[pkrvmq0rgcvqdmg:05913] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe3b0a5a6f]
[pkrvmq0rgcvqdmg:05913] [ 8] plumed_master(+0x146dd)[0x5572bb4f56dd]
[pkrvmq0rgcvqdmg:05913] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe3ac2a1ca]
[pkrvmq0rgcvqdmg:05913] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe3ac2a28b]
[pkrvmq0rgcvqdmg:05913] [11] plumed_master(+0x15365)[0x5572bb4f6365]
[pkrvmq0rgcvqdmg:05913] *** End of error message ***
</pre>
{% endraw %}

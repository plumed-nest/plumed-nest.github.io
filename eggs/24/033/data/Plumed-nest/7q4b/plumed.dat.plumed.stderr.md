**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmmklqx:05954] *** Process received signal ***
[runnervmmklqx:05954] Signal: Aborted (6)
[runnervmmklqx:05954] Signal code:  (-6)
[runnervmmklqx:05954] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7704e45330]
[runnervmmklqx:05954] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7704e9eb2c]
[runnervmmklqx:05954] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7704e4527e]
[runnervmmklqx:05954] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7704e288ff]
[runnervmmklqx:05954] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77052a5ff5]
[runnervmmklqx:05954] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77052bb0da]
[runnervmmklqx:05954] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77052a5a55]
[runnervmmklqx:05954] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77052a5a6f]
[runnervmmklqx:05954] [ 8] plumed(+0x146dd)[0x562ec28b66dd]
[runnervmmklqx:05954] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7704e2a1ca]
[runnervmmklqx:05954] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7704e2a28b]
[runnervmmklqx:05954] [11] plumed(+0x15365)[0x562ec28b7365]
[runnervmmklqx:05954] *** End of error message ***
</pre>
{% endraw %}

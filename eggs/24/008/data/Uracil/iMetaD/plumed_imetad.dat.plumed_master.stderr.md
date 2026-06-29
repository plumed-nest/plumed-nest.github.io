**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Uracil/iMetaD/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmmklqx:05341] *** Process received signal ***
[runnervmmklqx:05341] Signal: Aborted (6)
[runnervmmklqx:05341] Signal code:  (-6)
[runnervmmklqx:05341] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd2e9045330]
[runnervmmklqx:05341] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd2e909eb2c]
[runnervmmklqx:05341] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd2e904527e]
[runnervmmklqx:05341] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2e90288ff]
[runnervmmklqx:05341] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2e94a5ff5]
[runnervmmklqx:05341] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2e94bb0da]
[runnervmmklqx:05341] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2e94a5a55]
[runnervmmklqx:05341] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2e94a5a6f]
[runnervmmklqx:05341] [ 8] plumed_master(+0x146dd)[0x55bc9801f6dd]
[runnervmmklqx:05341] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd2e902a1ca]
[runnervmmklqx:05341] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd2e902a28b]
[runnervmmklqx:05341] [11] plumed_master(+0x15365)[0x55bc98020365]
[runnervmmklqx:05341] *** End of error message ***
</pre>
{% endraw %}

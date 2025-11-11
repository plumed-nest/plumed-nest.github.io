**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervmw9dnm:07606] *** Process received signal ***
[runnervmw9dnm:07606] Signal: Aborted (6)
[runnervmw9dnm:07606] Signal code:  (-6)
[runnervmw9dnm:07606] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb40c245330]
[runnervmw9dnm:07606] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb40c29eb2c]
[runnervmw9dnm:07606] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb40c24527e]
[runnervmw9dnm:07606] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb40c2288ff]
[runnervmw9dnm:07606] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb40c6a5ff5]
[runnervmw9dnm:07606] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb40c6bb0da]
[runnervmw9dnm:07606] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb40c6a5a55]
[runnervmw9dnm:07606] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb40c6a5a6f]
[runnervmw9dnm:07606] [ 8] plumed_master(+0x146dd)[0x55ef4fe556dd]
[runnervmw9dnm:07606] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb40c22a1ca]
[runnervmw9dnm:07606] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb40c22a28b]
[runnervmw9dnm:07606] [11] plumed_master(+0x15365)[0x55ef4fe56365]
[runnervmw9dnm:07606] *** End of error message ***
</pre>
{% endraw %}

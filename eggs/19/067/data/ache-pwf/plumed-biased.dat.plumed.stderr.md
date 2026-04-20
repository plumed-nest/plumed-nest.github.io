**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmeorf1:09518] *** Process received signal ***
[runnervmeorf1:09518] Signal: Aborted (6)
[runnervmeorf1:09518] Signal code:  (-6)
[runnervmeorf1:09518] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f16c9045330]
[runnervmeorf1:09518] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f16c909eb2c]
[runnervmeorf1:09518] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f16c904527e]
[runnervmeorf1:09518] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f16c90288ff]
[runnervmeorf1:09518] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f16c94a5ff5]
[runnervmeorf1:09518] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f16c94bb0da]
[runnervmeorf1:09518] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f16c94a5a55]
[runnervmeorf1:09518] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f16c94a5a6f]
[runnervmeorf1:09518] [ 8] plumed(+0x146dd)[0x556812e376dd]
[runnervmeorf1:09518] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f16c902a1ca]
[runnervmeorf1:09518] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f16c902a28b]
[runnervmeorf1:09518] [11] plumed(+0x15365)[0x556812e38365]
[runnervmeorf1:09518] *** End of error message ***
</pre>
{% endraw %}

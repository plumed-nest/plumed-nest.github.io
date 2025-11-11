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
[runnervmw9dnm:11240] *** Process received signal ***
[runnervmw9dnm:11240] Signal: Aborted (6)
[runnervmw9dnm:11240] Signal code:  (-6)
[runnervmw9dnm:11240] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0ccd445330]
[runnervmw9dnm:11240] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0ccd49eb2c]
[runnervmw9dnm:11240] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0ccd44527e]
[runnervmw9dnm:11240] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0ccd4288ff]
[runnervmw9dnm:11240] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0ccd8a5ff5]
[runnervmw9dnm:11240] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0ccd8bb0da]
[runnervmw9dnm:11240] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0ccd8a5a55]
[runnervmw9dnm:11240] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0ccd8a5a6f]
[runnervmw9dnm:11240] [ 8] plumed(+0x146dd)[0x55b8464df6dd]
[runnervmw9dnm:11240] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0ccd42a1ca]
[runnervmw9dnm:11240] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0ccd42a28b]
[runnervmw9dnm:11240] [11] plumed(+0x15365)[0x55b8464e0365]
[runnervmw9dnm:11240] *** End of error message ***
</pre>
{% endraw %}

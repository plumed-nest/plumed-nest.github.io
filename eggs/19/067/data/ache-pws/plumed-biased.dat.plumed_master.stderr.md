**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmw9dnm:11336] *** Process received signal ***
[runnervmw9dnm:11336] Signal: Aborted (6)
[runnervmw9dnm:11336] Signal code:  (-6)
[runnervmw9dnm:11336] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6072a45330]
[runnervmw9dnm:11336] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6072a9eb2c]
[runnervmw9dnm:11336] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6072a4527e]
[runnervmw9dnm:11336] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6072a288ff]
[runnervmw9dnm:11336] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6072ea5ff5]
[runnervmw9dnm:11336] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6072ebb0da]
[runnervmw9dnm:11336] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6072ea5a55]
[runnervmw9dnm:11336] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6072ea5a6f]
[runnervmw9dnm:11336] [ 8] plumed_master(+0x146dd)[0x5558ffefd6dd]
[runnervmw9dnm:11336] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6072a2a1ca]
[runnervmw9dnm:11336] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6072a2a28b]
[runnervmw9dnm:11336] [11] plumed_master(+0x15365)[0x5558ffefe365]
[runnervmw9dnm:11336] *** End of error message ***
</pre>
{% endraw %}

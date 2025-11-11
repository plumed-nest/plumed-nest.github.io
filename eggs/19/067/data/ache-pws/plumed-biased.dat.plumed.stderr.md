**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmw9dnm:11320] *** Process received signal ***
[runnervmw9dnm:11320] Signal: Aborted (6)
[runnervmw9dnm:11320] Signal code:  (-6)
[runnervmw9dnm:11320] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f95cea45330]
[runnervmw9dnm:11320] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f95cea9eb2c]
[runnervmw9dnm:11320] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f95cea4527e]
[runnervmw9dnm:11320] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95cea288ff]
[runnervmw9dnm:11320] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95ceea5ff5]
[runnervmw9dnm:11320] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95ceebb0da]
[runnervmw9dnm:11320] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95ceea5a55]
[runnervmw9dnm:11320] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95ceea5a6f]
[runnervmw9dnm:11320] [ 8] plumed(+0x146dd)[0x5612426996dd]
[runnervmw9dnm:11320] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f95cea2a1ca]
[runnervmw9dnm:11320] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f95cea2a28b]
[runnervmw9dnm:11320] [11] plumed(+0x15365)[0x56124269a365]
[runnervmw9dnm:11320] *** End of error message ***
</pre>
{% endraw %}

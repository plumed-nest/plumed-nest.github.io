**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmw9dnm:07880] *** Process received signal ***
[runnervmw9dnm:07880] Signal: Aborted (6)
[runnervmw9dnm:07880] Signal code:  (-6)
[runnervmw9dnm:07880] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f074e445330]
[runnervmw9dnm:07880] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f074e49eb2c]
[runnervmw9dnm:07880] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f074e44527e]
[runnervmw9dnm:07880] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f074e4288ff]
[runnervmw9dnm:07880] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f074e8a5ff5]
[runnervmw9dnm:07880] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f074e8bb0da]
[runnervmw9dnm:07880] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f074e8a5a55]
[runnervmw9dnm:07880] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f074e8a5a6f]
[runnervmw9dnm:07880] [ 8] plumed(+0x146dd)[0x55f4bfdaa6dd]
[runnervmw9dnm:07880] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f074e42a1ca]
[runnervmw9dnm:07880] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f074e42a28b]
[runnervmw9dnm:07880] [11] plumed(+0x15365)[0x55f4bfdab365]
[runnervmw9dnm:07880] *** End of error message ***
</pre>
{% endraw %}

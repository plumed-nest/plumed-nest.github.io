**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmw9dnm:07278] *** Process received signal ***
[runnervmw9dnm:07278] Signal: Aborted (6)
[runnervmw9dnm:07278] Signal code:  (-6)
[runnervmw9dnm:07278] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5ee3845330]
[runnervmw9dnm:07278] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5ee389eb2c]
[runnervmw9dnm:07278] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5ee384527e]
[runnervmw9dnm:07278] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5ee38288ff]
[runnervmw9dnm:07278] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5ee3ca5ff5]
[runnervmw9dnm:07278] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5ee3cbb0da]
[runnervmw9dnm:07278] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5ee3ca5a55]
[runnervmw9dnm:07278] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5ee3ca5a6f]
[runnervmw9dnm:07278] [ 8] plumed(+0x146dd)[0x5653bae126dd]
[runnervmw9dnm:07278] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5ee382a1ca]
[runnervmw9dnm:07278] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5ee382a28b]
[runnervmw9dnm:07278] [11] plumed(+0x15365)[0x5653bae13365]
[runnervmw9dnm:07278] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmw9dnm:07931] *** Process received signal ***
[runnervmw9dnm:07931] Signal: Aborted (6)
[runnervmw9dnm:07931] Signal code:  (-6)
[runnervmw9dnm:07931] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f620a445330]
[runnervmw9dnm:07931] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f620a49eb2c]
[runnervmw9dnm:07931] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f620a44527e]
[runnervmw9dnm:07931] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f620a4288ff]
[runnervmw9dnm:07931] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f620a8a5ff5]
[runnervmw9dnm:07931] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f620a8bb0da]
[runnervmw9dnm:07931] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f620a8a5a55]
[runnervmw9dnm:07931] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f620a8a5a6f]
[runnervmw9dnm:07931] [ 8] plumed(+0x146dd)[0x55fca43336dd]
[runnervmw9dnm:07931] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f620a42a1ca]
[runnervmw9dnm:07931] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f620a42a28b]
[runnervmw9dnm:07931] [11] plumed(+0x15365)[0x55fca4334365]
[runnervmw9dnm:07931] *** End of error message ***
</pre>
{% endraw %}

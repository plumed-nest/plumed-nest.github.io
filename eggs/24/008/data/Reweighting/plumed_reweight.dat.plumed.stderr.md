**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmmklqx:05257] *** Process received signal ***
[runnervmmklqx:05257] Signal: Aborted (6)
[runnervmmklqx:05257] Signal code:  (-6)
[runnervmmklqx:05257] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc66f445330]
[runnervmmklqx:05257] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc66f49eb2c]
[runnervmmklqx:05257] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc66f44527e]
[runnervmmklqx:05257] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc66f4288ff]
[runnervmmklqx:05257] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc66f8a5ff5]
[runnervmmklqx:05257] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc66f8bb0da]
[runnervmmklqx:05257] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc66f8a5a55]
[runnervmmklqx:05257] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc66f8a5a6f]
[runnervmmklqx:05257] [ 8] plumed(+0x146dd)[0x556e959706dd]
[runnervmmklqx:05257] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc66f42a1ca]
[runnervmmklqx:05257] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc66f42a28b]
[runnervmmklqx:05257] [11] plumed(+0x15365)[0x556e95971365]
[runnervmmklqx:05257] *** End of error message ***
</pre>
{% endraw %}

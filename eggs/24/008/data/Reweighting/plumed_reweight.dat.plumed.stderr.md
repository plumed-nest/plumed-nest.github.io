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
[runnervmkj6or:04918] *** Process received signal ***
[runnervmkj6or:04918] Signal: Aborted (6)
[runnervmkj6or:04918] Signal code:  (-6)
[runnervmkj6or:04918] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5d9845330]
[runnervmkj6or:04918] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5d989eb2c]
[runnervmkj6or:04918] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5d984527e]
[runnervmkj6or:04918] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5d98288ff]
[runnervmkj6or:04918] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5d9ca5ff5]
[runnervmkj6or:04918] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5d9cbb0da]
[runnervmkj6or:04918] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5d9ca5a55]
[runnervmkj6or:04918] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5d9ca5a6f]
[runnervmkj6or:04918] [ 8] plumed(+0x146dd)[0x564d262286dd]
[runnervmkj6or:04918] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5d982a1ca]
[runnervmkj6or:04918] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5d982a28b]
[runnervmkj6or:04918] [11] plumed(+0x15365)[0x564d26229365]
[runnervmkj6or:04918] *** End of error message ***
</pre>
{% endraw %}

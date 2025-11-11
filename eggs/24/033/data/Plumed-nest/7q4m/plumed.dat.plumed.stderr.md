**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmw9dnm:06220] *** Process received signal ***
[runnervmw9dnm:06220] Signal: Aborted (6)
[runnervmw9dnm:06220] Signal code:  (-6)
[runnervmw9dnm:06220] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f09445330]
[runnervmw9dnm:06220] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f0949eb2c]
[runnervmw9dnm:06220] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f0944527e]
[runnervmw9dnm:06220] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f094288ff]
[runnervmw9dnm:06220] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f098a5ff5]
[runnervmw9dnm:06220] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f098bb0da]
[runnervmw9dnm:06220] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f098a5a55]
[runnervmw9dnm:06220] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f098a5a6f]
[runnervmw9dnm:06220] [ 8] plumed(+0x146dd)[0x56053c1746dd]
[runnervmw9dnm:06220] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f0942a1ca]
[runnervmw9dnm:06220] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f0942a28b]
[runnervmw9dnm:06220] [11] plumed(+0x15365)[0x56053c175365]
[runnervmw9dnm:06220] *** End of error message ***
</pre>
{% endraw %}

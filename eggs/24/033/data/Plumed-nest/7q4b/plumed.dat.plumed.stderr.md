**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmw9dnm:06025] *** Process received signal ***
[runnervmw9dnm:06025] Signal: Aborted (6)
[runnervmw9dnm:06025] Signal code:  (-6)
[runnervmw9dnm:06025] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7782045330]
[runnervmw9dnm:06025] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f778209eb2c]
[runnervmw9dnm:06025] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f778204527e]
[runnervmw9dnm:06025] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77820288ff]
[runnervmw9dnm:06025] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77824a5ff5]
[runnervmw9dnm:06025] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77824bb0da]
[runnervmw9dnm:06025] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77824a5a55]
[runnervmw9dnm:06025] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77824a5a6f]
[runnervmw9dnm:06025] [ 8] plumed(+0x146dd)[0x559fae1f96dd]
[runnervmw9dnm:06025] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f778202a1ca]
[runnervmw9dnm:06025] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f778202a28b]
[runnervmw9dnm:06025] [11] plumed(+0x15365)[0x559fae1fa365]
[runnervmw9dnm:06025] *** End of error message ***
</pre>
{% endraw %}

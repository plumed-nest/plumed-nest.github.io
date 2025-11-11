**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmw9dnm:06041] *** Process received signal ***
[runnervmw9dnm:06041] Signal: Aborted (6)
[runnervmw9dnm:06041] Signal code:  (-6)
[runnervmw9dnm:06041] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fee3d845330]
[runnervmw9dnm:06041] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fee3d89eb2c]
[runnervmw9dnm:06041] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fee3d84527e]
[runnervmw9dnm:06041] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fee3d8288ff]
[runnervmw9dnm:06041] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fee3dca5ff5]
[runnervmw9dnm:06041] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fee3dcbb0da]
[runnervmw9dnm:06041] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fee3dca5a55]
[runnervmw9dnm:06041] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fee3dca5a6f]
[runnervmw9dnm:06041] [ 8] plumed_master(+0x146dd)[0x55b50deef6dd]
[runnervmw9dnm:06041] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fee3d82a1ca]
[runnervmw9dnm:06041] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fee3d82a28b]
[runnervmw9dnm:06041] [11] plumed_master(+0x15365)[0x55b50def0365]
[runnervmw9dnm:06041] *** End of error message ***
</pre>
{% endraw %}

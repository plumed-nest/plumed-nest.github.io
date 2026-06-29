**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./crys/4-reweight_crys.dat   
Download: [zipped raw stdout](4-reweight_crys.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_crys.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s33 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:04768] *** Process received signal ***
[runnervmmklqx:04768] Signal: Aborted (6)
[runnervmmklqx:04768] Signal code:  (-6)
[runnervmmklqx:04768] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa90dc45330]
[runnervmmklqx:04768] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa90dc9eb2c]
[runnervmmklqx:04768] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa90dc4527e]
[runnervmmklqx:04768] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa90dc288ff]
[runnervmmklqx:04768] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa90e0a5ff5]
[runnervmmklqx:04768] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa90e0bb0da]
[runnervmmklqx:04768] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa90e0a5a55]
[runnervmmklqx:04768] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa90e0a5a6f]
[runnervmmklqx:04768] [ 8] plumed_master(+0x146dd)[0x55a69b7526dd]
[runnervmmklqx:04768] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa90dc2a1ca]
[runnervmmklqx:04768] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa90dc2a28b]
[runnervmmklqx:04768] [11] plumed_master(+0x15365)[0x55a69b753365]
[runnervmmklqx:04768] *** End of error message ***
</pre>
{% endraw %}

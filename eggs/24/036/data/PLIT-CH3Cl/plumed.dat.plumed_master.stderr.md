**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervmw9dnm:06954] *** Process received signal ***
[runnervmw9dnm:06954] Signal: Aborted (6)
[runnervmw9dnm:06954] Signal code:  (-6)
[runnervmw9dnm:06954] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa824045330]
[runnervmw9dnm:06954] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa82409eb2c]
[runnervmw9dnm:06954] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa82404527e]
[runnervmw9dnm:06954] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa8240288ff]
[runnervmw9dnm:06954] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa8244a5ff5]
[runnervmw9dnm:06954] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa8244bb0da]
[runnervmw9dnm:06954] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa8244a5a55]
[runnervmw9dnm:06954] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa8244a5a6f]
[runnervmw9dnm:06954] [ 8] plumed_master(+0x146dd)[0x55efd6af66dd]
[runnervmw9dnm:06954] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa82402a1ca]
[runnervmw9dnm:06954] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa82402a28b]
[runnervmw9dnm:06954] [11] plumed_master(+0x15365)[0x55efd6af7365]
[runnervmw9dnm:06954] *** End of error message ***
</pre>
{% endraw %}

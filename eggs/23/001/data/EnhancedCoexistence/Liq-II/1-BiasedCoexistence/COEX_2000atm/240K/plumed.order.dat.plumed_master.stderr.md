**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmw9dnm:08219] *** Process received signal ***
[runnervmw9dnm:08219] Signal: Aborted (6)
[runnervmw9dnm:08219] Signal code:  (-6)
[runnervmw9dnm:08219] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f20a9045330]
[runnervmw9dnm:08219] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f20a909eb2c]
[runnervmw9dnm:08219] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f20a904527e]
[runnervmw9dnm:08219] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f20a90288ff]
[runnervmw9dnm:08219] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f20a94a5ff5]
[runnervmw9dnm:08219] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f20a94bb0da]
[runnervmw9dnm:08219] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f20a94a5a55]
[runnervmw9dnm:08219] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f20a94a5a6f]
[runnervmw9dnm:08219] [ 8] plumed_master(+0x146dd)[0x5617b26af6dd]
[runnervmw9dnm:08219] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f20a902a1ca]
[runnervmw9dnm:08219] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f20a902a28b]
[runnervmw9dnm:08219] [11] plumed_master(+0x15365)[0x5617b26b0365]
[runnervmw9dnm:08219] *** End of error message ***
</pre>
{% endraw %}

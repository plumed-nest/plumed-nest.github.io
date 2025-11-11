**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmw9dnm:08169] *** Process received signal ***
[runnervmw9dnm:08169] Signal: Aborted (6)
[runnervmw9dnm:08169] Signal code:  (-6)
[runnervmw9dnm:08169] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f549b245330]
[runnervmw9dnm:08169] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f549b29eb2c]
[runnervmw9dnm:08169] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f549b24527e]
[runnervmw9dnm:08169] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f549b2288ff]
[runnervmw9dnm:08169] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f549b6a5ff5]
[runnervmw9dnm:08169] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f549b6bb0da]
[runnervmw9dnm:08169] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f549b6a5a55]
[runnervmw9dnm:08169] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f549b6a5a6f]
[runnervmw9dnm:08169] [ 8] plumed_master(+0x146dd)[0x55c8335676dd]
[runnervmw9dnm:08169] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f549b22a1ca]
[runnervmw9dnm:08169] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f549b22a28b]
[runnervmw9dnm:08169] [11] plumed_master(+0x15365)[0x55c833568365]
[runnervmw9dnm:08169] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmw9dnm:08270] *** Process received signal ***
[runnervmw9dnm:08270] Signal: Aborted (6)
[runnervmw9dnm:08270] Signal code:  (-6)
[runnervmw9dnm:08270] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f228d245330]
[runnervmw9dnm:08270] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f228d29eb2c]
[runnervmw9dnm:08270] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f228d24527e]
[runnervmw9dnm:08270] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f228d2288ff]
[runnervmw9dnm:08270] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f228d6a5ff5]
[runnervmw9dnm:08270] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f228d6bb0da]
[runnervmw9dnm:08270] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f228d6a5a55]
[runnervmw9dnm:08270] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f228d6a5a6f]
[runnervmw9dnm:08270] [ 8] plumed_master(+0x146dd)[0x55799822a6dd]
[runnervmw9dnm:08270] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f228d22a1ca]
[runnervmw9dnm:08270] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f228d22a28b]
[runnervmw9dnm:08270] [11] plumed_master(+0x15365)[0x55799822b365]
[runnervmw9dnm:08270] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmw9dnm:08255] *** Process received signal ***
[runnervmw9dnm:08255] Signal: Aborted (6)
[runnervmw9dnm:08255] Signal code:  (-6)
[runnervmw9dnm:08255] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd92e845330]
[runnervmw9dnm:08255] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd92e89eb2c]
[runnervmw9dnm:08255] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd92e84527e]
[runnervmw9dnm:08255] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd92e8288ff]
[runnervmw9dnm:08255] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd92eca5ff5]
[runnervmw9dnm:08255] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd92ecbb0da]
[runnervmw9dnm:08255] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd92eca5a55]
[runnervmw9dnm:08255] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd92eca5a6f]
[runnervmw9dnm:08255] [ 8] plumed(+0x146dd)[0x55a46222d6dd]
[runnervmw9dnm:08255] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd92e82a1ca]
[runnervmw9dnm:08255] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd92e82a28b]
[runnervmw9dnm:08255] [11] plumed(+0x15365)[0x55a46222e365]
[runnervmw9dnm:08255] *** End of error message ***
</pre>
{% endraw %}

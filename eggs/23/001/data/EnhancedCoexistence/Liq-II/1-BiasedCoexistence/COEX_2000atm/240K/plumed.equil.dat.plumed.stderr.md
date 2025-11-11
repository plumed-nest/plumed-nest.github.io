**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmw9dnm:08153] *** Process received signal ***
[runnervmw9dnm:08153] Signal: Aborted (6)
[runnervmw9dnm:08153] Signal code:  (-6)
[runnervmw9dnm:08153] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7791845330]
[runnervmw9dnm:08153] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f779189eb2c]
[runnervmw9dnm:08153] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f779184527e]
[runnervmw9dnm:08153] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77918288ff]
[runnervmw9dnm:08153] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7791ca5ff5]
[runnervmw9dnm:08153] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7791cbb0da]
[runnervmw9dnm:08153] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7791ca5a55]
[runnervmw9dnm:08153] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7791ca5a6f]
[runnervmw9dnm:08153] [ 8] plumed(+0x146dd)[0x5628f7cd76dd]
[runnervmw9dnm:08153] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f779182a1ca]
[runnervmw9dnm:08153] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f779182a28b]
[runnervmw9dnm:08153] [11] plumed(+0x15365)[0x5628f7cd8365]
[runnervmw9dnm:08153] *** End of error message ***
</pre>
{% endraw %}

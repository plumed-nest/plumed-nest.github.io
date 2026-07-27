**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervmvrwv9:06791] *** Process received signal ***
[runnervmvrwv9:06791] Signal: Aborted (6)
[runnervmvrwv9:06791] Signal code:  (-6)
[runnervmvrwv9:06791] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8a1a445330]
[runnervmvrwv9:06791] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8a1a49eb2c]
[runnervmvrwv9:06791] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8a1a44527e]
[runnervmvrwv9:06791] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8a1a4288ff]
[runnervmvrwv9:06791] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8a1a8a5ff5]
[runnervmvrwv9:06791] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8a1a8bb0da]
[runnervmvrwv9:06791] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8a1a8a5a55]
[runnervmvrwv9:06791] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8a1a8a5a6f]
[runnervmvrwv9:06791] [ 8] plumed(+0x146dd)[0x55d513a716dd]
[runnervmvrwv9:06791] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8a1a42a1ca]
[runnervmvrwv9:06791] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8a1a42a28b]
[runnervmvrwv9:06791] [11] plumed(+0x15365)[0x55d513a72365]
[runnervmvrwv9:06791] *** End of error message ***
</pre>
{% endraw %}

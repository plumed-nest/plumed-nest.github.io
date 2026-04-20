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
[runnervmeorf1:08649] *** Process received signal ***
[runnervmeorf1:08649] Signal: Aborted (6)
[runnervmeorf1:08649] Signal code:  (-6)
[runnervmeorf1:08649] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f06d9245330]
[runnervmeorf1:08649] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f06d929eb2c]
[runnervmeorf1:08649] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f06d924527e]
[runnervmeorf1:08649] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06d92288ff]
[runnervmeorf1:08649] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06d96a5ff5]
[runnervmeorf1:08649] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06d96bb0da]
[runnervmeorf1:08649] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06d96a5a55]
[runnervmeorf1:08649] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06d96a5a6f]
[runnervmeorf1:08649] [ 8] plumed(+0x146dd)[0x55d8333aa6dd]
[runnervmeorf1:08649] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f06d922a1ca]
[runnervmeorf1:08649] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f06d922a28b]
[runnervmeorf1:08649] [11] plumed(+0x15365)[0x55d8333ab365]
[runnervmeorf1:08649] *** End of error message ***
</pre>
{% endraw %}

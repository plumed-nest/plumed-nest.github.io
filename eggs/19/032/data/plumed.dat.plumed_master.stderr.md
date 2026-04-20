**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[runnervmeorf1:11286] *** Process received signal ***
[runnervmeorf1:11286] Signal: Aborted (6)
[runnervmeorf1:11286] Signal code:  (-6)
[runnervmeorf1:11286] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7667845330]
[runnervmeorf1:11286] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f766789eb2c]
[runnervmeorf1:11286] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f766784527e]
[runnervmeorf1:11286] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76678288ff]
[runnervmeorf1:11286] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7667ca5ff5]
[runnervmeorf1:11286] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7667cbb0da]
[runnervmeorf1:11286] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7667ca5a55]
[runnervmeorf1:11286] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7667ca5a6f]
[runnervmeorf1:11286] [ 8] plumed_master(+0x146dd)[0x558e79b886dd]
[runnervmeorf1:11286] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f766782a1ca]
[runnervmeorf1:11286] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f766782a28b]
[runnervmeorf1:11286] [11] plumed_master(+0x15365)[0x558e79b89365]
[runnervmeorf1:11286] *** End of error message ***
</pre>
{% endraw %}

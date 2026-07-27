**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[runnervmvrwv9:10818] *** Process received signal ***
[runnervmvrwv9:10818] Signal: Aborted (6)
[runnervmvrwv9:10818] Signal code:  (-6)
[runnervmvrwv9:10818] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f367aa45330]
[runnervmvrwv9:10818] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f367aa9eb2c]
[runnervmvrwv9:10818] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f367aa4527e]
[runnervmvrwv9:10818] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f367aa288ff]
[runnervmvrwv9:10818] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f367aea5ff5]
[runnervmvrwv9:10818] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f367aebb0da]
[runnervmvrwv9:10818] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f367aea5a55]
[runnervmvrwv9:10818] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f367aea5a6f]
[runnervmvrwv9:10818] [ 8] plumed_master(+0x146dd)[0x55c8089856dd]
[runnervmvrwv9:10818] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f367aa2a1ca]
[runnervmvrwv9:10818] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f367aa2a28b]
[runnervmvrwv9:10818] [11] plumed_master(+0x15365)[0x55c808986365]
[runnervmvrwv9:10818] *** End of error message ***
</pre>
{% endraw %}

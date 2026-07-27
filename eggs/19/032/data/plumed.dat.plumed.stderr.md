**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[runnervmvrwv9:10802] *** Process received signal ***
[runnervmvrwv9:10802] Signal: Aborted (6)
[runnervmvrwv9:10802] Signal code:  (-6)
[runnervmvrwv9:10802] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe414e45330]
[runnervmvrwv9:10802] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe414e9eb2c]
[runnervmvrwv9:10802] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe414e4527e]
[runnervmvrwv9:10802] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe414e288ff]
[runnervmvrwv9:10802] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe4152a5ff5]
[runnervmvrwv9:10802] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe4152bb0da]
[runnervmvrwv9:10802] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe4152a5a55]
[runnervmvrwv9:10802] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe4152a5a6f]
[runnervmvrwv9:10802] [ 8] plumed(+0x146dd)[0x55aa0161a6dd]
[runnervmvrwv9:10802] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe414e2a1ca]
[runnervmvrwv9:10802] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe414e2a28b]
[runnervmvrwv9:10802] [11] plumed(+0x15365)[0x55aa0161b365]
[runnervmvrwv9:10802] *** End of error message ***
</pre>
{% endraw %}

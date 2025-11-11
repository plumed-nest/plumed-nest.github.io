**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[runnervmw9dnm:11262] *** Process received signal ***
[runnervmw9dnm:11262] Signal: Aborted (6)
[runnervmw9dnm:11262] Signal code:  (-6)
[runnervmw9dnm:11262] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9bfce45330]
[runnervmw9dnm:11262] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9bfce9eb2c]
[runnervmw9dnm:11262] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9bfce4527e]
[runnervmw9dnm:11262] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9bfce288ff]
[runnervmw9dnm:11262] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9bfd2a5ff5]
[runnervmw9dnm:11262] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9bfd2bb0da]
[runnervmw9dnm:11262] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9bfd2a5a55]
[runnervmw9dnm:11262] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9bfd2a5a6f]
[runnervmw9dnm:11262] [ 8] plumed(+0x146dd)[0x55d63fa7c6dd]
[runnervmw9dnm:11262] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9bfce2a1ca]
[runnervmw9dnm:11262] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9bfce2a28b]
[runnervmw9dnm:11262] [11] plumed(+0x15365)[0x55d63fa7d365]
[runnervmw9dnm:11262] *** End of error message ***
</pre>
{% endraw %}

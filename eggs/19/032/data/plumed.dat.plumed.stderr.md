**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[fv-az1937-158:67619] *** Process received signal ***
[fv-az1937-158:67619] Signal: Aborted (6)
[fv-az1937-158:67619] Signal code:  (-6)
[fv-az1937-158:67619] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e12c45330]
[fv-az1937-158:67619] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e12c9eb2c]
[fv-az1937-158:67619] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e12c4527e]
[fv-az1937-158:67619] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e12c288ff]
[fv-az1937-158:67619] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e130a5ff5]
[fv-az1937-158:67619] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e130bb0da]
[fv-az1937-158:67619] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e130a5a55]
[fv-az1937-158:67619] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e130a5a6f]
[fv-az1937-158:67619] [ 8] plumed(+0x146dd)[0x564519cff6dd]
[fv-az1937-158:67619] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e12c2a1ca]
[fv-az1937-158:67619] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e12c2a28b]
[fv-az1937-158:67619] [11] plumed(+0x15365)[0x564519d00365]
[fv-az1937-158:67619] *** End of error message ***
</pre>
{% endraw %}

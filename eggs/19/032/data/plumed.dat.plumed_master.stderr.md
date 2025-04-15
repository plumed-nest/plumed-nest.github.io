**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[fv-az1910-428:68579] *** Process received signal ***
[fv-az1910-428:68579] Signal: Aborted (6)
[fv-az1910-428:68579] Signal code:  (-6)
[fv-az1910-428:68579] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f7d445330]
[fv-az1910-428:68579] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f7d49eb2c]
[fv-az1910-428:68579] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f7d44527e]
[fv-az1910-428:68579] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f7d4288ff]
[fv-az1910-428:68579] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f7d8a5ff5]
[fv-az1910-428:68579] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f7d8bb0da]
[fv-az1910-428:68579] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f7d8a5a55]
[fv-az1910-428:68579] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f7d8a5a6f]
[fv-az1910-428:68579] [ 8] plumed_master(+0x146dd)[0x563b646216dd]
[fv-az1910-428:68579] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f7d42a1ca]
[fv-az1910-428:68579] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f7d42a28b]
[fv-az1910-428:68579] [11] plumed_master(+0x15365)[0x563b64622365]
[fv-az1910-428:68579] *** End of error message ***
</pre>
{% endraw %}

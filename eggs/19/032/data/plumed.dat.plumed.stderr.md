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
[pkrvmbietmlfzoi:68177] *** Process received signal ***
[pkrvmbietmlfzoi:68177] Signal: Aborted (6)
[pkrvmbietmlfzoi:68177] Signal code:  (-6)
[pkrvmbietmlfzoi:68177] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7741845330]
[pkrvmbietmlfzoi:68177] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f774189eb2c]
[pkrvmbietmlfzoi:68177] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f774184527e]
[pkrvmbietmlfzoi:68177] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77418288ff]
[pkrvmbietmlfzoi:68177] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7741ca5ff5]
[pkrvmbietmlfzoi:68177] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7741cbb0da]
[pkrvmbietmlfzoi:68177] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7741ca5a55]
[pkrvmbietmlfzoi:68177] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7741ca5a6f]
[pkrvmbietmlfzoi:68177] [ 8] plumed(+0x146dd)[0x55e984bd36dd]
[pkrvmbietmlfzoi:68177] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f774182a1ca]
[pkrvmbietmlfzoi:68177] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f774182a28b]
[pkrvmbietmlfzoi:68177] [11] plumed(+0x15365)[0x55e984bd4365]
[pkrvmbietmlfzoi:68177] *** End of error message ***
</pre>
{% endraw %}

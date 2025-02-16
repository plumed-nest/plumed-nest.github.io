**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[fv-az1937-158:67635] *** Process received signal ***
[fv-az1937-158:67635] Signal: Aborted (6)
[fv-az1937-158:67635] Signal code:  (-6)
[fv-az1937-158:67635] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc4fa45330]
[fv-az1937-158:67635] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc4fa9eb2c]
[fv-az1937-158:67635] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc4fa4527e]
[fv-az1937-158:67635] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc4fa288ff]
[fv-az1937-158:67635] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc4fea5ff5]
[fv-az1937-158:67635] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc4febb0da]
[fv-az1937-158:67635] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc4fea5a55]
[fv-az1937-158:67635] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc4fea5a6f]
[fv-az1937-158:67635] [ 8] plumed_master(+0x146dd)[0x55836cf986dd]
[fv-az1937-158:67635] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc4fa2a1ca]
[fv-az1937-158:67635] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc4fa2a28b]
[fv-az1937-158:67635] [11] plumed_master(+0x15365)[0x55836cf99365]
[fv-az1937-158:67635] *** End of error message ***
</pre>
{% endraw %}

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
[fv-az1624-565:11469] *** Process received signal ***
[fv-az1624-565:11469] Signal: Aborted (6)
[fv-az1624-565:11469] Signal code:  (-6)
[fv-az1624-565:11469] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe3a4e45330]
[fv-az1624-565:11469] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe3a4e9eb2c]
[fv-az1624-565:11469] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe3a4e4527e]
[fv-az1624-565:11469] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3a4e288ff]
[fv-az1624-565:11469] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3a52a5ff5]
[fv-az1624-565:11469] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3a52bb0da]
[fv-az1624-565:11469] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3a52a5a55]
[fv-az1624-565:11469] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3a52a5a6f]
[fv-az1624-565:11469] [ 8] plumed_master(+0x146dd)[0x56401a3206dd]
[fv-az1624-565:11469] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe3a4e2a1ca]
[fv-az1624-565:11469] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe3a4e2a28b]
[fv-az1624-565:11469] [11] plumed_master(+0x15365)[0x56401a321365]
[fv-az1624-565:11469] *** End of error message ***
</pre>
{% endraw %}

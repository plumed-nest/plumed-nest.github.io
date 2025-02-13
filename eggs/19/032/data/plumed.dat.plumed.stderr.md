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
[fv-az1657-925:11269] *** Process received signal ***
[fv-az1657-925:11269] Signal: Aborted (6)
[fv-az1657-925:11269] Signal code:  (-6)
[fv-az1657-925:11269] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f992e845330]
[fv-az1657-925:11269] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f992e89eb2c]
[fv-az1657-925:11269] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f992e84527e]
[fv-az1657-925:11269] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f992e8288ff]
[fv-az1657-925:11269] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f992eca5ff5]
[fv-az1657-925:11269] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f992ecbb0da]
[fv-az1657-925:11269] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f992eca5a55]
[fv-az1657-925:11269] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f992eca5a6f]
[fv-az1657-925:11269] [ 8] plumed(+0x146dd)[0x562abf9026dd]
[fv-az1657-925:11269] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f992e82a1ca]
[fv-az1657-925:11269] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f992e82a28b]
[fv-az1657-925:11269] [11] plumed(+0x15365)[0x562abf903365]
[fv-az1657-925:11269] *** End of error message ***
</pre>
{% endraw %}

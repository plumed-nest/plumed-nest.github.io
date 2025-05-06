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
[fv-az1050-229:67937] *** Process received signal ***
[fv-az1050-229:67937] Signal: Aborted (6)
[fv-az1050-229:67937] Signal code:  (-6)
[fv-az1050-229:67937] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8df045330]
[fv-az1050-229:67937] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8df09eb2c]
[fv-az1050-229:67937] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8df04527e]
[fv-az1050-229:67937] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8df0288ff]
[fv-az1050-229:67937] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8df4a5ff5]
[fv-az1050-229:67937] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8df4bb0da]
[fv-az1050-229:67937] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8df4a5a55]
[fv-az1050-229:67937] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8df4a5a6f]
[fv-az1050-229:67937] [ 8] plumed_master(+0x146dd)[0x56365b8d96dd]
[fv-az1050-229:67937] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8df02a1ca]
[fv-az1050-229:67937] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8df02a28b]
[fv-az1050-229:67937] [11] plumed_master(+0x15365)[0x56365b8da365]
[fv-az1050-229:67937] *** End of error message ***
</pre>
{% endraw %}

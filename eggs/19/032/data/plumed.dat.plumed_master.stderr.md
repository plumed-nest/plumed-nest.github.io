**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[pkrvmxyh4eaekms:11706] *** Process received signal ***
[pkrvmxyh4eaekms:11706] Signal: Aborted (6)
[pkrvmxyh4eaekms:11706] Signal code:  (-6)
[pkrvmxyh4eaekms:11706] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f66b0845330]
[pkrvmxyh4eaekms:11706] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f66b089eb2c]
[pkrvmxyh4eaekms:11706] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f66b084527e]
[pkrvmxyh4eaekms:11706] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66b08288ff]
[pkrvmxyh4eaekms:11706] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66b0ca5ff5]
[pkrvmxyh4eaekms:11706] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66b0cbb0da]
[pkrvmxyh4eaekms:11706] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66b0ca5a55]
[pkrvmxyh4eaekms:11706] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66b0ca5a6f]
[pkrvmxyh4eaekms:11706] [ 8] plumed_master(+0x146dd)[0x55a2156c26dd]
[pkrvmxyh4eaekms:11706] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f66b082a1ca]
[pkrvmxyh4eaekms:11706] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f66b082a28b]
[pkrvmxyh4eaekms:11706] [11] plumed_master(+0x15365)[0x55a2156c3365]
[pkrvmxyh4eaekms:11706] *** End of error message ***
</pre>
{% endraw %}

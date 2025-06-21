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
[pkrvmxyh4eaekms:11690] *** Process received signal ***
[pkrvmxyh4eaekms:11690] Signal: Aborted (6)
[pkrvmxyh4eaekms:11690] Signal code:  (-6)
[pkrvmxyh4eaekms:11690] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3cd5a45330]
[pkrvmxyh4eaekms:11690] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3cd5a9eb2c]
[pkrvmxyh4eaekms:11690] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3cd5a4527e]
[pkrvmxyh4eaekms:11690] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3cd5a288ff]
[pkrvmxyh4eaekms:11690] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3cd5ea5ff5]
[pkrvmxyh4eaekms:11690] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3cd5ebb0da]
[pkrvmxyh4eaekms:11690] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3cd5ea5a55]
[pkrvmxyh4eaekms:11690] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3cd5ea5a6f]
[pkrvmxyh4eaekms:11690] [ 8] plumed(+0x146dd)[0x56195dd716dd]
[pkrvmxyh4eaekms:11690] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3cd5a2a1ca]
[pkrvmxyh4eaekms:11690] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3cd5a2a28b]
[pkrvmxyh4eaekms:11690] [11] plumed(+0x15365)[0x56195dd72365]
[pkrvmxyh4eaekms:11690] *** End of error message ***
</pre>
{% endraw %}

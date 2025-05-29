**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmf6wy0o8zjz:64246] *** Process received signal ***
[pkrvmf6wy0o8zjz:64246] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64246] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64246] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca5b845330]
[pkrvmf6wy0o8zjz:64246] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca5b89eb2c]
[pkrvmf6wy0o8zjz:64246] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca5b84527e]
[pkrvmf6wy0o8zjz:64246] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca5b8288ff]
[pkrvmf6wy0o8zjz:64246] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca5bca5ff5]
[pkrvmf6wy0o8zjz:64246] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca5bcbb0da]
[pkrvmf6wy0o8zjz:64246] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca5bca5a55]
[pkrvmf6wy0o8zjz:64246] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca5bca5a6f]
[pkrvmf6wy0o8zjz:64246] [ 8] plumed_master(+0x146dd)[0x55a663a356dd]
[pkrvmf6wy0o8zjz:64246] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca5b82a1ca]
[pkrvmf6wy0o8zjz:64246] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca5b82a28b]
[pkrvmf6wy0o8zjz:64246] [11] plumed_master(+0x15365)[0x55a663a36365]
[pkrvmf6wy0o8zjz:64246] *** End of error message ***
</pre>
{% endraw %}

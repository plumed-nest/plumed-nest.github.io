**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmf6wy0o8zjz:64282] *** Process received signal ***
[pkrvmf6wy0o8zjz:64282] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64282] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64282] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c58845330]
[pkrvmf6wy0o8zjz:64282] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c5889eb2c]
[pkrvmf6wy0o8zjz:64282] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c5884527e]
[pkrvmf6wy0o8zjz:64282] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c588288ff]
[pkrvmf6wy0o8zjz:64282] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c58ca5ff5]
[pkrvmf6wy0o8zjz:64282] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c58cbb0da]
[pkrvmf6wy0o8zjz:64282] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c58ca5a55]
[pkrvmf6wy0o8zjz:64282] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c58ca5a6f]
[pkrvmf6wy0o8zjz:64282] [ 8] plumed(+0x146dd)[0x55ae026016dd]
[pkrvmf6wy0o8zjz:64282] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c5882a1ca]
[pkrvmf6wy0o8zjz:64282] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c5882a28b]
[pkrvmf6wy0o8zjz:64282] [11] plumed(+0x15365)[0x55ae02602365]
[pkrvmf6wy0o8zjz:64282] *** End of error message ***
</pre>
{% endraw %}

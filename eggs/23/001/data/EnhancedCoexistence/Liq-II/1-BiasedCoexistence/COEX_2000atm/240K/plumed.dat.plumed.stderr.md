**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[pkrvmf6wy0o8zjz:64178] *** Process received signal ***
[pkrvmf6wy0o8zjz:64178] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:64178] Signal code:  (-6)
[pkrvmf6wy0o8zjz:64178] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8c42045330]
[pkrvmf6wy0o8zjz:64178] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8c4209eb2c]
[pkrvmf6wy0o8zjz:64178] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8c4204527e]
[pkrvmf6wy0o8zjz:64178] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8c420288ff]
[pkrvmf6wy0o8zjz:64178] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8c424a5ff5]
[pkrvmf6wy0o8zjz:64178] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8c424bb0da]
[pkrvmf6wy0o8zjz:64178] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8c424a5a55]
[pkrvmf6wy0o8zjz:64178] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8c424a5a6f]
[pkrvmf6wy0o8zjz:64178] [ 8] plumed(+0x146dd)[0x557e38ccb6dd]
[pkrvmf6wy0o8zjz:64178] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8c4202a1ca]
[pkrvmf6wy0o8zjz:64178] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8c4202a28b]
[pkrvmf6wy0o8zjz:64178] [11] plumed(+0x15365)[0x557e38ccc365]
[pkrvmf6wy0o8zjz:64178] *** End of error message ***
</pre>
{% endraw %}

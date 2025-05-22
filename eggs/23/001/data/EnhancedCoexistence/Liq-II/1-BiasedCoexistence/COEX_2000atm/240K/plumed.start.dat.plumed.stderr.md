**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmf6wy0o8zjz:35030] *** Process received signal ***
[pkrvmf6wy0o8zjz:35030] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:35030] Signal code:  (-6)
[pkrvmf6wy0o8zjz:35030] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc7b6c45330]
[pkrvmf6wy0o8zjz:35030] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc7b6c9eb2c]
[pkrvmf6wy0o8zjz:35030] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc7b6c4527e]
[pkrvmf6wy0o8zjz:35030] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7b6c288ff]
[pkrvmf6wy0o8zjz:35030] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7b70a5ff5]
[pkrvmf6wy0o8zjz:35030] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7b70bb0da]
[pkrvmf6wy0o8zjz:35030] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7b70a5a55]
[pkrvmf6wy0o8zjz:35030] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7b70a5a6f]
[pkrvmf6wy0o8zjz:35030] [ 8] plumed(+0x146dd)[0x5620137786dd]
[pkrvmf6wy0o8zjz:35030] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc7b6c2a1ca]
[pkrvmf6wy0o8zjz:35030] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc7b6c2a28b]
[pkrvmf6wy0o8zjz:35030] [11] plumed(+0x15365)[0x562013779365]
[pkrvmf6wy0o8zjz:35030] *** End of error message ***
</pre>
{% endraw %}

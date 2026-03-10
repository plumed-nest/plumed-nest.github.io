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
[runnervm0kj6c:06530] *** Process received signal ***
[runnervm0kj6c:06530] Signal: Aborted (6)
[runnervm0kj6c:06530] Signal code:  (-6)
[runnervm0kj6c:06530] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe8f4845330]
[runnervm0kj6c:06530] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe8f489eb2c]
[runnervm0kj6c:06530] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe8f484527e]
[runnervm0kj6c:06530] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe8f48288ff]
[runnervm0kj6c:06530] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe8f4ca5ff5]
[runnervm0kj6c:06530] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe8f4cbb0da]
[runnervm0kj6c:06530] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe8f4ca5a55]
[runnervm0kj6c:06530] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe8f4ca5a6f]
[runnervm0kj6c:06530] [ 8] plumed(+0x146dd)[0x56379e1a16dd]
[runnervm0kj6c:06530] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe8f482a1ca]
[runnervm0kj6c:06530] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe8f482a28b]
[runnervm0kj6c:06530] [11] plumed(+0x15365)[0x56379e1a2365]
[runnervm0kj6c:06530] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[runnervm0kj6c:06546] *** Process received signal ***
[runnervm0kj6c:06546] Signal: Aborted (6)
[runnervm0kj6c:06546] Signal code:  (-6)
[runnervm0kj6c:06546] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa16ec45330]
[runnervm0kj6c:06546] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa16ec9eb2c]
[runnervm0kj6c:06546] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa16ec4527e]
[runnervm0kj6c:06546] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa16ec288ff]
[runnervm0kj6c:06546] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa16f0a5ff5]
[runnervm0kj6c:06546] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa16f0bb0da]
[runnervm0kj6c:06546] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa16f0a5a55]
[runnervm0kj6c:06546] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa16f0a5a6f]
[runnervm0kj6c:06546] [ 8] plumed_master(+0x146dd)[0x561d5c1786dd]
[runnervm0kj6c:06546] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa16ec2a1ca]
[runnervm0kj6c:06546] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa16ec2a28b]
[runnervm0kj6c:06546] [11] plumed_master(+0x15365)[0x561d5c179365]
[runnervm0kj6c:06546] *** End of error message ***
</pre>
{% endraw %}

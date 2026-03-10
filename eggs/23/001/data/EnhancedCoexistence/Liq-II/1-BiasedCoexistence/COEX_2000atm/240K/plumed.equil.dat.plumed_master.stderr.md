**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[runnervm0kj6c:06597] *** Process received signal ***
[runnervm0kj6c:06597] Signal: Aborted (6)
[runnervm0kj6c:06597] Signal code:  (-6)
[runnervm0kj6c:06597] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5db1845330]
[runnervm0kj6c:06597] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5db189eb2c]
[runnervm0kj6c:06597] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5db184527e]
[runnervm0kj6c:06597] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5db18288ff]
[runnervm0kj6c:06597] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5db1ca5ff5]
[runnervm0kj6c:06597] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5db1cbb0da]
[runnervm0kj6c:06597] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5db1ca5a55]
[runnervm0kj6c:06597] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5db1ca5a6f]
[runnervm0kj6c:06597] [ 8] plumed_master(+0x146dd)[0x55dc96df36dd]
[runnervm0kj6c:06597] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5db182a1ca]
[runnervm0kj6c:06597] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5db182a28b]
[runnervm0kj6c:06597] [11] plumed_master(+0x15365)[0x55dc96df4365]
[runnervm0kj6c:06597] *** End of error message ***
</pre>
{% endraw %}

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
[runnervm0kj6c:06683] *** Process received signal ***
[runnervm0kj6c:06683] Signal: Aborted (6)
[runnervm0kj6c:06683] Signal code:  (-6)
[runnervm0kj6c:06683] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feeac845330]
[runnervm0kj6c:06683] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feeac89eb2c]
[runnervm0kj6c:06683] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feeac84527e]
[runnervm0kj6c:06683] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feeac8288ff]
[runnervm0kj6c:06683] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feeacca5ff5]
[runnervm0kj6c:06683] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feeaccbb0da]
[runnervm0kj6c:06683] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feeacca5a55]
[runnervm0kj6c:06683] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feeacca5a6f]
[runnervm0kj6c:06683] [ 8] plumed(+0x146dd)[0x55a0a96c46dd]
[runnervm0kj6c:06683] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feeac82a1ca]
[runnervm0kj6c:06683] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feeac82a28b]
[runnervm0kj6c:06683] [11] plumed(+0x15365)[0x55a0a96c5365]
[runnervm0kj6c:06683] *** End of error message ***
</pre>
{% endraw %}

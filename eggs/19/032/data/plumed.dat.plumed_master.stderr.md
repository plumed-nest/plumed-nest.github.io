**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[runnervm76f27:11699] *** Process received signal ***
[runnervm76f27:11699] Signal: Aborted (6)
[runnervm76f27:11699] Signal code:  (-6)
[runnervm76f27:11699] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd61b845330]
[runnervm76f27:11699] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd61b89ec0c]
[runnervm76f27:11699] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd61b84527e]
[runnervm76f27:11699] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd61b8288ff]
[runnervm76f27:11699] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd61bca5ff5]
[runnervm76f27:11699] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd61bcbb0da]
[runnervm76f27:11699] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd61bca5a55]
[runnervm76f27:11699] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd61bca5a6f]
[runnervm76f27:11699] [ 8] plumed_master(+0x146dd)[0x5567f9a586dd]
[runnervm76f27:11699] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd61b82a1ca]
[runnervm76f27:11699] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd61b82a28b]
[runnervm76f27:11699] [11] plumed_master(+0x15365)[0x5567f9a59365]
[runnervm76f27:11699] *** End of error message ***
</pre>
{% endraw %}

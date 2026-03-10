**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervm0kj6c:06164] *** Process received signal ***
[runnervm0kj6c:06164] Signal: Aborted (6)
[runnervm0kj6c:06164] Signal code:  (-6)
[runnervm0kj6c:06164] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb93f045330]
[runnervm0kj6c:06164] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb93f09eb2c]
[runnervm0kj6c:06164] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb93f04527e]
[runnervm0kj6c:06164] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb93f0288ff]
[runnervm0kj6c:06164] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb93f4a5ff5]
[runnervm0kj6c:06164] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb93f4bb0da]
[runnervm0kj6c:06164] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb93f4a5a55]
[runnervm0kj6c:06164] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb93f4a5a6f]
[runnervm0kj6c:06164] [ 8] plumed_master(+0x146dd)[0x55ae191686dd]
[runnervm0kj6c:06164] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb93f02a1ca]
[runnervm0kj6c:06164] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb93f02a28b]
[runnervm0kj6c:06164] [11] plumed_master(+0x15365)[0x55ae19169365]
[runnervm0kj6c:06164] *** End of error message ***
</pre>
{% endraw %}

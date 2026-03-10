**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w1.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervm0kj6c:04734] *** Process received signal ***
[runnervm0kj6c:04734] Signal: Aborted (6)
[runnervm0kj6c:04734] Signal code:  (-6)
[runnervm0kj6c:04734] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f358e445330]
[runnervm0kj6c:04734] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f358e49eb2c]
[runnervm0kj6c:04734] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f358e44527e]
[runnervm0kj6c:04734] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f358e4288ff]
[runnervm0kj6c:04734] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f358e8a5ff5]
[runnervm0kj6c:04734] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f358e8bb0da]
[runnervm0kj6c:04734] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f358e8a5a55]
[runnervm0kj6c:04734] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f358e8a5a6f]
[runnervm0kj6c:04734] [ 8] plumed_master(+0x146dd)[0x55a67b5f86dd]
[runnervm0kj6c:04734] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f358e42a1ca]
[runnervm0kj6c:04734] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f358e42a28b]
[runnervm0kj6c:04734] [11] plumed_master(+0x15365)[0x55a67b5f9365]
[runnervm0kj6c:04734] *** End of error message ***
</pre>
{% endraw %}

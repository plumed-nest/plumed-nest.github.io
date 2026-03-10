**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w0.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w0.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w0.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervm0kj6c:04695] *** Process received signal ***
[runnervm0kj6c:04695] Signal: Aborted (6)
[runnervm0kj6c:04695] Signal code:  (-6)
[runnervm0kj6c:04695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe3af045330]
[runnervm0kj6c:04695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe3af09eb2c]
[runnervm0kj6c:04695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe3af04527e]
[runnervm0kj6c:04695] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3af0288ff]
[runnervm0kj6c:04695] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3af4a5ff5]
[runnervm0kj6c:04695] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3af4bb0da]
[runnervm0kj6c:04695] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3af4a5a55]
[runnervm0kj6c:04695] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3af4a5a6f]
[runnervm0kj6c:04695] [ 8] plumed_master(+0x146dd)[0x562b93a7e6dd]
[runnervm0kj6c:04695] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe3af02a1ca]
[runnervm0kj6c:04695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe3af02a28b]
[runnervm0kj6c:04695] [11] plumed_master(+0x15365)[0x562b93a7f365]
[runnervm0kj6c:04695] *** End of error message ***
</pre>
{% endraw %}

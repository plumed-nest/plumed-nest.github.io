**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervm0kj6c:09798] *** Process received signal ***
[runnervm0kj6c:09798] Signal: Aborted (6)
[runnervm0kj6c:09798] Signal code:  (-6)
[runnervm0kj6c:09798] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f957ee45330]
[runnervm0kj6c:09798] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f957ee9eb2c]
[runnervm0kj6c:09798] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f957ee4527e]
[runnervm0kj6c:09798] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f957ee288ff]
[runnervm0kj6c:09798] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f957f2a5ff5]
[runnervm0kj6c:09798] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f957f2bb0da]
[runnervm0kj6c:09798] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f957f2a5a55]
[runnervm0kj6c:09798] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f957f2a5a6f]
[runnervm0kj6c:09798] [ 8] plumed_master(+0x146dd)[0x55a2002026dd]
[runnervm0kj6c:09798] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f957ee2a1ca]
[runnervm0kj6c:09798] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f957ee2a28b]
[runnervm0kj6c:09798] [11] plumed_master(+0x15365)[0x55a200203365]
[runnervm0kj6c:09798] *** End of error message ***
</pre>
{% endraw %}

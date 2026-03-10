**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervm0kj6c:10008] *** Process received signal ***
[runnervm0kj6c:10008] Signal: Aborted (6)
[runnervm0kj6c:10008] Signal code:  (-6)
[runnervm0kj6c:10008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f41c3245330]
[runnervm0kj6c:10008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f41c329eb2c]
[runnervm0kj6c:10008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f41c324527e]
[runnervm0kj6c:10008] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41c32288ff]
[runnervm0kj6c:10008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41c36a5ff5]
[runnervm0kj6c:10008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41c36bb0da]
[runnervm0kj6c:10008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41c36a5a55]
[runnervm0kj6c:10008] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41c36a5a6f]
[runnervm0kj6c:10008] [ 8] plumed_master(+0x146dd)[0x55ef89bfe6dd]
[runnervm0kj6c:10008] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f41c322a1ca]
[runnervm0kj6c:10008] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f41c322a28b]
[runnervm0kj6c:10008] [11] plumed_master(+0x15365)[0x55ef89bff365]
[runnervm0kj6c:10008] *** End of error message ***
</pre>
{% endraw %}

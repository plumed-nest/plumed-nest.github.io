**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervm0kj6c:12534] *** Process received signal ***
[runnervm0kj6c:12534] Signal: Aborted (6)
[runnervm0kj6c:12534] Signal code:  (-6)
[runnervm0kj6c:12534] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2cbb645330]
[runnervm0kj6c:12534] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2cbb69eb2c]
[runnervm0kj6c:12534] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2cbb64527e]
[runnervm0kj6c:12534] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2cbb6288ff]
[runnervm0kj6c:12534] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2cbbaa5ff5]
[runnervm0kj6c:12534] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2cbbabb0da]
[runnervm0kj6c:12534] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2cbbaa5a55]
[runnervm0kj6c:12534] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2cbbaa5a6f]
[runnervm0kj6c:12534] [ 8] plumed_master(+0x146dd)[0x55f9b4e5b6dd]
[runnervm0kj6c:12534] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2cbb62a1ca]
[runnervm0kj6c:12534] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2cbb62a28b]
[runnervm0kj6c:12534] [11] plumed_master(+0x15365)[0x55f9b4e5c365]
[runnervm0kj6c:12534] *** End of error message ***
</pre>
{% endraw %}

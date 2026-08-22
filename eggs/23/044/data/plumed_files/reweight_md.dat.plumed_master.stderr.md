**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervm76f27:05208] *** Process received signal ***
[runnervm76f27:05208] Signal: Aborted (6)
[runnervm76f27:05208] Signal code:  (-6)
[runnervm76f27:05208] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd455245330]
[runnervm76f27:05208] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd45529ec0c]
[runnervm76f27:05208] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd45524527e]
[runnervm76f27:05208] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4552288ff]
[runnervm76f27:05208] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4556a5ff5]
[runnervm76f27:05208] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4556bb0da]
[runnervm76f27:05208] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4556a5a55]
[runnervm76f27:05208] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4556a5a6f]
[runnervm76f27:05208] [ 8] plumed_master(+0x146dd)[0x5591a85fe6dd]
[runnervm76f27:05208] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd45522a1ca]
[runnervm76f27:05208] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd45522a28b]
[runnervm76f27:05208] [11] plumed_master(+0x15365)[0x5591a85ff365]
[runnervm76f27:05208] *** End of error message ***
</pre>
{% endraw %}

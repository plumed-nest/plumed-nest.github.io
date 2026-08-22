**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w0.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w0.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w0.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervm76f27:05607] *** Process received signal ***
[runnervm76f27:05607] Signal: Aborted (6)
[runnervm76f27:05607] Signal code:  (-6)
[runnervm76f27:05607] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc485845330]
[runnervm76f27:05607] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc48589ec0c]
[runnervm76f27:05607] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc48584527e]
[runnervm76f27:05607] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4858288ff]
[runnervm76f27:05607] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc485ca5ff5]
[runnervm76f27:05607] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc485cbb0da]
[runnervm76f27:05607] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc485ca5a55]
[runnervm76f27:05607] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc485ca5a6f]
[runnervm76f27:05607] [ 8] plumed_master(+0x146dd)[0x5611742966dd]
[runnervm76f27:05607] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc48582a1ca]
[runnervm76f27:05607] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc48582a28b]
[runnervm76f27:05607] [11] plumed_master(+0x15365)[0x561174297365]
[runnervm76f27:05607] *** End of error message ***
</pre>
{% endraw %}

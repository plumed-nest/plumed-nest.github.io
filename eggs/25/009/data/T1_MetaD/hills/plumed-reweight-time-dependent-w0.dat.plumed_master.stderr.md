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
[runnervmkj6or:04237] *** Process received signal ***
[runnervmkj6or:04237] Signal: Aborted (6)
[runnervmkj6or:04237] Signal code:  (-6)
[runnervmkj6or:04237] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd116e45330]
[runnervmkj6or:04237] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd116e9eb2c]
[runnervmkj6or:04237] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd116e4527e]
[runnervmkj6or:04237] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd116e288ff]
[runnervmkj6or:04237] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1172a5ff5]
[runnervmkj6or:04237] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1172bb0da]
[runnervmkj6or:04237] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1172a5a55]
[runnervmkj6or:04237] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1172a5a6f]
[runnervmkj6or:04237] [ 8] plumed_master(+0x146dd)[0x55d8e36486dd]
[runnervmkj6or:04237] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd116e2a1ca]
[runnervmkj6or:04237] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd116e2a28b]
[runnervmkj6or:04237] [11] plumed_master(+0x15365)[0x55d8e3649365]
[runnervmkj6or:04237] *** End of error message ***
</pre>
{% endraw %}

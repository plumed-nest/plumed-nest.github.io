**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @50 : keyword ARG is compulsory for this action
[runnervm76f27:09989] *** Process received signal ***
[runnervm76f27:09989] Signal: Aborted (6)
[runnervm76f27:09989] Signal code:  (-6)
[runnervm76f27:09989] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa327045330]
[runnervm76f27:09989] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa32709ec0c]
[runnervm76f27:09989] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa32704527e]
[runnervm76f27:09989] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3270288ff]
[runnervm76f27:09989] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3274a5ff5]
[runnervm76f27:09989] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3274bb0da]
[runnervm76f27:09989] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3274a5a55]
[runnervm76f27:09989] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3274a5a6f]
[runnervm76f27:09989] [ 8] plumed_master(+0x146dd)[0x556cab9bb6dd]
[runnervm76f27:09989] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa32702a1ca]
[runnervm76f27:09989] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa32702a28b]
[runnervm76f27:09989] [11] plumed_master(+0x15365)[0x556cab9bc365]
[runnervm76f27:09989] *** End of error message ***
</pre>
{% endraw %}

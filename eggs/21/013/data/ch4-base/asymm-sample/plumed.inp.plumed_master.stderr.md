**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[runnervm76f27:09884] *** Process received signal ***
[runnervm76f27:09884] Signal: Aborted (6)
[runnervm76f27:09884] Signal code:  (-6)
[runnervm76f27:09884] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f330fe45330]
[runnervm76f27:09884] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f330fe9ec0c]
[runnervm76f27:09884] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f330fe4527e]
[runnervm76f27:09884] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f330fe288ff]
[runnervm76f27:09884] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f33102a5ff5]
[runnervm76f27:09884] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f33102bb0da]
[runnervm76f27:09884] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f33102a5a55]
[runnervm76f27:09884] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f33102a5a6f]
[runnervm76f27:09884] [ 8] plumed_master(+0x146dd)[0x5648e24d66dd]
[runnervm76f27:09884] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f330fe2a1ca]
[runnervm76f27:09884] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f330fe2a28b]
[runnervm76f27:09884] [11] plumed_master(+0x15365)[0x5648e24d7365]
[runnervm76f27:09884] *** End of error message ***
</pre>
{% endraw %}

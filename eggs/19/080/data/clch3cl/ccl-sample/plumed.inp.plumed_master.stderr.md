**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervm76f27:10365] *** Process received signal ***
[runnervm76f27:10365] Signal: Aborted (6)
[runnervm76f27:10365] Signal code:  (-6)
[runnervm76f27:10365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3284c45330]
[runnervm76f27:10365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3284c9ec0c]
[runnervm76f27:10365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3284c4527e]
[runnervm76f27:10365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3284c288ff]
[runnervm76f27:10365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32850a5ff5]
[runnervm76f27:10365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32850bb0da]
[runnervm76f27:10365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32850a5a55]
[runnervm76f27:10365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32850a5a6f]
[runnervm76f27:10365] [ 8] plumed_master(+0x146dd)[0x55f60446b6dd]
[runnervm76f27:10365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3284c2a1ca]
[runnervm76f27:10365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3284c2a28b]
[runnervm76f27:10365] [11] plumed_master(+0x15365)[0x55f60446c365]
[runnervm76f27:10365] *** End of error message ***
</pre>
{% endraw %}

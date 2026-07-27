**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmvrwv9:09979] *** Process received signal ***
[runnervmvrwv9:09979] Signal: Aborted (6)
[runnervmvrwv9:09979] Signal code:  (-6)
[runnervmvrwv9:09979] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6da6445330]
[runnervmvrwv9:09979] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6da649eb2c]
[runnervmvrwv9:09979] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6da644527e]
[runnervmvrwv9:09979] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6da64288ff]
[runnervmvrwv9:09979] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6da68a5ff5]
[runnervmvrwv9:09979] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6da68bb0da]
[runnervmvrwv9:09979] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6da68a5a55]
[runnervmvrwv9:09979] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6da68a5a6f]
[runnervmvrwv9:09979] [ 8] plumed_master(+0x146dd)[0x55b5b46266dd]
[runnervmvrwv9:09979] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6da642a1ca]
[runnervmvrwv9:09979] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6da642a28b]
[runnervmvrwv9:09979] [11] plumed_master(+0x15365)[0x55b5b4627365]
[runnervmvrwv9:09979] *** End of error message ***
</pre>
{% endraw %}

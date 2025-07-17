**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @42 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:09848] *** Process received signal ***
[pkrvmq0rgcvqdmg:09848] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09848] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09848] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f676aa45330]
[pkrvmq0rgcvqdmg:09848] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f676aa9eb2c]
[pkrvmq0rgcvqdmg:09848] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f676aa4527e]
[pkrvmq0rgcvqdmg:09848] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f676aa288ff]
[pkrvmq0rgcvqdmg:09848] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f676aea5ff5]
[pkrvmq0rgcvqdmg:09848] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f676aebb0da]
[pkrvmq0rgcvqdmg:09848] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f676aea5a55]
[pkrvmq0rgcvqdmg:09848] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f676aea5a6f]
[pkrvmq0rgcvqdmg:09848] [ 8] plumed_master(+0x146dd)[0x558c166376dd]
[pkrvmq0rgcvqdmg:09848] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f676aa2a1ca]
[pkrvmq0rgcvqdmg:09848] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f676aa2a28b]
[pkrvmq0rgcvqdmg:09848] [11] plumed_master(+0x15365)[0x558c16638365]
[pkrvmq0rgcvqdmg:09848] *** End of error message ***
</pre>
{% endraw %}

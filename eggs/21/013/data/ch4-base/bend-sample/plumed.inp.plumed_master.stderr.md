**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[runnervmkj6or:11664] *** Process received signal ***
[runnervmkj6or:11664] Signal: Aborted (6)
[runnervmkj6or:11664] Signal code:  (-6)
[runnervmkj6or:11664] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83a6c45330]
[runnervmkj6or:11664] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83a6c9eb2c]
[runnervmkj6or:11664] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83a6c4527e]
[runnervmkj6or:11664] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83a6c288ff]
[runnervmkj6or:11664] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83a70a5ff5]
[runnervmkj6or:11664] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83a70bb0da]
[runnervmkj6or:11664] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83a70a5a55]
[runnervmkj6or:11664] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83a70a5a6f]
[runnervmkj6or:11664] [ 8] plumed_master(+0x146dd)[0x561ba0dc46dd]
[runnervmkj6or:11664] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83a6c2a1ca]
[runnervmkj6or:11664] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83a6c2a28b]
[runnervmkj6or:11664] [11] plumed_master(+0x15365)[0x561ba0dc5365]
[runnervmkj6or:11664] *** End of error message ***
</pre>
{% endraw %}

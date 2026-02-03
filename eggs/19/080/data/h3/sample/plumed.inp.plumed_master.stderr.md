**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmkj6or:11171] *** Process received signal ***
[runnervmkj6or:11171] Signal: Aborted (6)
[runnervmkj6or:11171] Signal code:  (-6)
[runnervmkj6or:11171] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fadc8845330]
[runnervmkj6or:11171] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fadc889eb2c]
[runnervmkj6or:11171] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fadc884527e]
[runnervmkj6or:11171] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fadc88288ff]
[runnervmkj6or:11171] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fadc8ca5ff5]
[runnervmkj6or:11171] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fadc8cbb0da]
[runnervmkj6or:11171] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fadc8ca5a55]
[runnervmkj6or:11171] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fadc8ca5a6f]
[runnervmkj6or:11171] [ 8] plumed_master(+0x146dd)[0x55ad85a416dd]
[runnervmkj6or:11171] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fadc882a1ca]
[runnervmkj6or:11171] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fadc882a28b]
[runnervmkj6or:11171] [11] plumed_master(+0x15365)[0x55ad85a42365]
[runnervmkj6or:11171] *** End of error message ***
</pre>
{% endraw %}

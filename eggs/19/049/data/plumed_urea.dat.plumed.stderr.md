**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[pkrvmq0rgcvqdmg:11739] *** Process received signal ***
[pkrvmq0rgcvqdmg:11739] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11739] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11739] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff65ea45330]
[pkrvmq0rgcvqdmg:11739] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff65ea9eb2c]
[pkrvmq0rgcvqdmg:11739] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff65ea4527e]
[pkrvmq0rgcvqdmg:11739] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff65ea288ff]
[pkrvmq0rgcvqdmg:11739] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff65eea5ff5]
[pkrvmq0rgcvqdmg:11739] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff65eebb0da]
[pkrvmq0rgcvqdmg:11739] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff65eea5a55]
[pkrvmq0rgcvqdmg:11739] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff65eea5a6f]
[pkrvmq0rgcvqdmg:11739] [ 8] plumed(+0x146dd)[0x55983ce8d6dd]
[pkrvmq0rgcvqdmg:11739] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff65ea2a1ca]
[pkrvmq0rgcvqdmg:11739] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff65ea2a28b]
[pkrvmq0rgcvqdmg:11739] [11] plumed(+0x15365)[0x55983ce8e365]
[pkrvmq0rgcvqdmg:11739] *** End of error message ***
</pre>
{% endraw %}

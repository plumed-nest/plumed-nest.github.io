**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmkj6or:11082] *** Process received signal ***
[runnervmkj6or:11082] Signal: Aborted (6)
[runnervmkj6or:11082] Signal code:  (-6)
[runnervmkj6or:11082] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c6c845330]
[runnervmkj6or:11082] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c6c89eb2c]
[runnervmkj6or:11082] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c6c84527e]
[runnervmkj6or:11082] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c6c8288ff]
[runnervmkj6or:11082] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c6cca5ff5]
[runnervmkj6or:11082] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c6ccbb0da]
[runnervmkj6or:11082] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c6cca5a55]
[runnervmkj6or:11082] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c6cca5a6f]
[runnervmkj6or:11082] [ 8] plumed_master(+0x146dd)[0x55f8ab0b26dd]
[runnervmkj6or:11082] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c6c82a1ca]
[runnervmkj6or:11082] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c6c82a28b]
[runnervmkj6or:11082] [11] plumed_master(+0x15365)[0x55f8ab0b3365]
[runnervmkj6or:11082] *** End of error message ***
</pre>
{% endraw %}

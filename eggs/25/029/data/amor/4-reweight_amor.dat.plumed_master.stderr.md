**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./amor/4-reweight_amor.dat   
Download: [zipped raw stdout](4-reweight_amor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_amor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[runnervmkj6or:04169] *** Process received signal ***
[runnervmkj6or:04169] Signal: Aborted (6)
[runnervmkj6or:04169] Signal code:  (-6)
[runnervmkj6or:04169] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5ce9c45330]
[runnervmkj6or:04169] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5ce9c9eb2c]
[runnervmkj6or:04169] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5ce9c4527e]
[runnervmkj6or:04169] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5ce9c288ff]
[runnervmkj6or:04169] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5cea0a5ff5]
[runnervmkj6or:04169] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5cea0bb0da]
[runnervmkj6or:04169] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5cea0a5a55]
[runnervmkj6or:04169] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5cea0a5a6f]
[runnervmkj6or:04169] [ 8] plumed_master(+0x146dd)[0x55da898bb6dd]
[runnervmkj6or:04169] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5ce9c2a1ca]
[runnervmkj6or:04169] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5ce9c2a28b]
[runnervmkj6or:04169] [11] plumed_master(+0x15365)[0x55da898bc365]
[runnervmkj6or:04169] *** End of error message ***
</pre>
{% endraw %}

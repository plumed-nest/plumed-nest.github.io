**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @38 : keyword ARG is compulsory for this action
[runnervmkj6or:05103] *** Process received signal ***
[runnervmkj6or:05103] Signal: Aborted (6)
[runnervmkj6or:05103] Signal code:  (-6)
[runnervmkj6or:05103] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fedd5645330]
[runnervmkj6or:05103] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fedd569eb2c]
[runnervmkj6or:05103] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fedd564527e]
[runnervmkj6or:05103] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fedd56288ff]
[runnervmkj6or:05103] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fedd5aa5ff5]
[runnervmkj6or:05103] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fedd5abb0da]
[runnervmkj6or:05103] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fedd5aa5a55]
[runnervmkj6or:05103] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fedd5aa5a6f]
[runnervmkj6or:05103] [ 8] plumed_master(+0x146dd)[0x55d76d6ca6dd]
[runnervmkj6or:05103] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fedd562a1ca]
[runnervmkj6or:05103] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fedd562a28b]
[runnervmkj6or:05103] [11] plumed_master(+0x15365)[0x55d76d6cb365]
[runnervmkj6or:05103] *** End of error message ***
</pre>
{% endraw %}

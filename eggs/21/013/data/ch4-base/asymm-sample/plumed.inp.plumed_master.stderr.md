**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[runnervmkj6or:11562] *** Process received signal ***
[runnervmkj6or:11562] Signal: Aborted (6)
[runnervmkj6or:11562] Signal code:  (-6)
[runnervmkj6or:11562] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe4cf645330]
[runnervmkj6or:11562] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe4cf69eb2c]
[runnervmkj6or:11562] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe4cf64527e]
[runnervmkj6or:11562] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4cf6288ff]
[runnervmkj6or:11562] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe4cfaa5ff5]
[runnervmkj6or:11562] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe4cfabb0da]
[runnervmkj6or:11562] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe4cfaa5a55]
[runnervmkj6or:11562] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe4cfaa5a6f]
[runnervmkj6or:11562] [ 8] plumed_master(+0x146dd)[0x5557513fb6dd]
[runnervmkj6or:11562] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe4cf62a1ca]
[runnervmkj6or:11562] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe4cf62a28b]
[runnervmkj6or:11562] [11] plumed_master(+0x15365)[0x5557513fc365]
[runnervmkj6or:11562] *** End of error message ***
</pre>
{% endraw %}

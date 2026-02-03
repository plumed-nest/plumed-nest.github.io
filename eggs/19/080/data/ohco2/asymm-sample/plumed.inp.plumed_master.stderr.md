**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmkj6or:10650] *** Process received signal ***
[runnervmkj6or:10650] Signal: Aborted (6)
[runnervmkj6or:10650] Signal code:  (-6)
[runnervmkj6or:10650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4f3a445330]
[runnervmkj6or:10650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4f3a49eb2c]
[runnervmkj6or:10650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4f3a44527e]
[runnervmkj6or:10650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4f3a4288ff]
[runnervmkj6or:10650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4f3a8a5ff5]
[runnervmkj6or:10650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4f3a8bb0da]
[runnervmkj6or:10650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4f3a8a5a55]
[runnervmkj6or:10650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4f3a8a5a6f]
[runnervmkj6or:10650] [ 8] plumed_master(+0x146dd)[0x561072ccf6dd]
[runnervmkj6or:10650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4f3a42a1ca]
[runnervmkj6or:10650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4f3a42a28b]
[runnervmkj6or:10650] [11] plumed_master(+0x15365)[0x561072cd0365]
[runnervmkj6or:10650] *** End of error message ***
</pre>
{% endraw %}

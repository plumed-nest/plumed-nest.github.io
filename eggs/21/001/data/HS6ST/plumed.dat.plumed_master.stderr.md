**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @37 : keyword ARG is compulsory for this action
[runnervmkj6or:08840] *** Process received signal ***
[runnervmkj6or:08840] Signal: Aborted (6)
[runnervmkj6or:08840] Signal code:  (-6)
[runnervmkj6or:08840] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca10845330]
[runnervmkj6or:08840] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca1089eb2c]
[runnervmkj6or:08840] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca1084527e]
[runnervmkj6or:08840] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca108288ff]
[runnervmkj6or:08840] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca10ca5ff5]
[runnervmkj6or:08840] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca10cbb0da]
[runnervmkj6or:08840] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca10ca5a55]
[runnervmkj6or:08840] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca10ca5a6f]
[runnervmkj6or:08840] [ 8] plumed_master(+0x146dd)[0x5639931c16dd]
[runnervmkj6or:08840] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca1082a1ca]
[runnervmkj6or:08840] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca1082a28b]
[runnervmkj6or:08840] [11] plumed_master(+0x15365)[0x5639931c2365]
[runnervmkj6or:08840] *** End of error message ***
</pre>
{% endraw %}

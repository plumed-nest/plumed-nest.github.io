**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT_A399V/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmkj6or:05245] *** Process received signal ***
[runnervmkj6or:05245] Signal: Aborted (6)
[runnervmkj6or:05245] Signal code:  (-6)
[runnervmkj6or:05245] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe121045330]
[runnervmkj6or:05245] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe12109eb2c]
[runnervmkj6or:05245] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe12104527e]
[runnervmkj6or:05245] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe1210288ff]
[runnervmkj6or:05245] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe1214a5ff5]
[runnervmkj6or:05245] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe1214bb0da]
[runnervmkj6or:05245] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe1214a5a55]
[runnervmkj6or:05245] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe1214a5a6f]
[runnervmkj6or:05245] [ 8] plumed_master(+0x146dd)[0x55fbe45c06dd]
[runnervmkj6or:05245] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe12102a1ca]
[runnervmkj6or:05245] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe12102a28b]
[runnervmkj6or:05245] [11] plumed_master(+0x15365)[0x55fbe45c1365]
[runnervmkj6or:05245] *** End of error message ***
</pre>
{% endraw %}

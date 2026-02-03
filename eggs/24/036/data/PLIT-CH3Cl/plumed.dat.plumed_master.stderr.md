**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervmkj6or:05168] *** Process received signal ***
[runnervmkj6or:05168] Signal: Aborted (6)
[runnervmkj6or:05168] Signal code:  (-6)
[runnervmkj6or:05168] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa829245330]
[runnervmkj6or:05168] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa82929eb2c]
[runnervmkj6or:05168] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa82924527e]
[runnervmkj6or:05168] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa8292288ff]
[runnervmkj6or:05168] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa8296a5ff5]
[runnervmkj6or:05168] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa8296bb0da]
[runnervmkj6or:05168] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa8296a5a55]
[runnervmkj6or:05168] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa8296a5a6f]
[runnervmkj6or:05168] [ 8] plumed_master(+0x146dd)[0x55676991a6dd]
[runnervmkj6or:05168] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa82922a1ca]
[runnervmkj6or:05168] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa82922a28b]
[runnervmkj6or:05168] [11] plumed_master(+0x15365)[0x55676991b365]
[runnervmkj6or:05168] *** End of error message ***
</pre>
{% endraw %}

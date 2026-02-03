**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @149 : keyword ARG is compulsory for this action
[runnervmkj6or:05161] *** Process received signal ***
[runnervmkj6or:05161] Signal: Aborted (6)
[runnervmkj6or:05161] Signal code:  (-6)
[runnervmkj6or:05161] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d26245330]
[runnervmkj6or:05161] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d2629eb2c]
[runnervmkj6or:05161] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d2624527e]
[runnervmkj6or:05161] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d262288ff]
[runnervmkj6or:05161] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d266a5ff5]
[runnervmkj6or:05161] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d266bb0da]
[runnervmkj6or:05161] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d266a5a55]
[runnervmkj6or:05161] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d266a5a6f]
[runnervmkj6or:05161] [ 8] plumed_master(+0x146dd)[0x5577d5fcf6dd]
[runnervmkj6or:05161] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d2622a1ca]
[runnervmkj6or:05161] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d2622a28b]
[runnervmkj6or:05161] [11] plumed_master(+0x15365)[0x5577d5fd0365]
[runnervmkj6or:05161] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @150 : keyword ARG is compulsory for this action
[runnervmmklqx:07043] *** Process received signal ***
[runnervmmklqx:07043] Signal: Aborted (6)
[runnervmmklqx:07043] Signal code:  (-6)
[runnervmmklqx:07043] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcfe0245330]
[runnervmmklqx:07043] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcfe029eb2c]
[runnervmmklqx:07043] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcfe024527e]
[runnervmmklqx:07043] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcfe02288ff]
[runnervmmklqx:07043] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcfe06a5ff5]
[runnervmmklqx:07043] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcfe06bb0da]
[runnervmmklqx:07043] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcfe06a5a55]
[runnervmmklqx:07043] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcfe06a5a6f]
[runnervmmklqx:07043] [ 8] plumed_master(+0x146dd)[0x55f6a82db6dd]
[runnervmmklqx:07043] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcfe022a1ca]
[runnervmmklqx:07043] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcfe022a28b]
[runnervmmklqx:07043] [11] plumed_master(+0x15365)[0x55f6a82dc365]
[runnervmmklqx:07043] *** End of error message ***
</pre>
{% endraw %}

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
[runnervmmtnos:32809] *** Process received signal ***
[runnervmmtnos:32809] Signal: Aborted (6)
[runnervmmtnos:32809] Signal code:  (-6)
[runnervmmtnos:32809] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ca8c45330]
[runnervmmtnos:32809] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ca8c9eb2c]
[runnervmmtnos:32809] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ca8c4527e]
[runnervmmtnos:32809] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ca8c288ff]
[runnervmmtnos:32809] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ca90a5ff5]
[runnervmmtnos:32809] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ca90bb0da]
[runnervmmtnos:32809] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ca90a5a55]
[runnervmmtnos:32809] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ca90a5a6f]
[runnervmmtnos:32809] [ 8] plumed_master(+0x146dd)[0x55efc480c6dd]
[runnervmmtnos:32809] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ca8c2a1ca]
[runnervmmtnos:32809] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ca8c2a28b]
[runnervmmtnos:32809] [11] plumed_master(+0x15365)[0x55efc480d365]
[runnervmmtnos:32809] *** End of error message ***
</pre>
{% endraw %}

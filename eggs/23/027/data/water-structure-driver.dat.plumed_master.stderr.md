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
ERROR in input to action DUMPGRID with label @150 : keyword ARG is compulsory for this action
[runnervmeorf1:07273] *** Process received signal ***
[runnervmeorf1:07273] Signal: Aborted (6)
[runnervmeorf1:07273] Signal code:  (-6)
[runnervmeorf1:07273] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f22bd645330]
[runnervmeorf1:07273] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f22bd69eb2c]
[runnervmeorf1:07273] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f22bd64527e]
[runnervmeorf1:07273] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f22bd6288ff]
[runnervmeorf1:07273] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f22bdaa5ff5]
[runnervmeorf1:07273] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f22bdabb0da]
[runnervmeorf1:07273] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f22bdaa5a55]
[runnervmeorf1:07273] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f22bdaa5a6f]
[runnervmeorf1:07273] [ 8] plumed_master(+0x146dd)[0x55e919e836dd]
[runnervmeorf1:07273] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f22bd62a1ca]
[runnervmeorf1:07273] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f22bd62a28b]
[runnervmeorf1:07273] [11] plumed_master(+0x15365)[0x55e919e84365]
[runnervmeorf1:07273] *** End of error message ***
</pre>
{% endraw %}

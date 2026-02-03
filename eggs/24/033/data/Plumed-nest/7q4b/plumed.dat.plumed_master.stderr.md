**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmkj6or:04618] *** Process received signal ***
[runnervmkj6or:04618] Signal: Aborted (6)
[runnervmkj6or:04618] Signal code:  (-6)
[runnervmkj6or:04618] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ab1045330]
[runnervmkj6or:04618] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ab109eb2c]
[runnervmkj6or:04618] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ab104527e]
[runnervmkj6or:04618] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ab10288ff]
[runnervmkj6or:04618] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ab14a5ff5]
[runnervmkj6or:04618] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ab14bb0da]
[runnervmkj6or:04618] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ab14a5a55]
[runnervmkj6or:04618] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ab14a5a6f]
[runnervmkj6or:04618] [ 8] plumed_master(+0x146dd)[0x563e70d1b6dd]
[runnervmkj6or:04618] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ab102a1ca]
[runnervmkj6or:04618] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ab102a28b]
[runnervmkj6or:04618] [11] plumed_master(+0x15365)[0x563e70d1c365]
[runnervmkj6or:04618] *** End of error message ***
</pre>
{% endraw %}

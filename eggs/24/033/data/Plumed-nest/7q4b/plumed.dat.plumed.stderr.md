**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmkj6or:04602] *** Process received signal ***
[runnervmkj6or:04602] Signal: Aborted (6)
[runnervmkj6or:04602] Signal code:  (-6)
[runnervmkj6or:04602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83cc645330]
[runnervmkj6or:04602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83cc69eb2c]
[runnervmkj6or:04602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83cc64527e]
[runnervmkj6or:04602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83cc6288ff]
[runnervmkj6or:04602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83ccaa5ff5]
[runnervmkj6or:04602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83ccabb0da]
[runnervmkj6or:04602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83ccaa5a55]
[runnervmkj6or:04602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83ccaa5a6f]
[runnervmkj6or:04602] [ 8] plumed(+0x146dd)[0x55c387f056dd]
[runnervmkj6or:04602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83cc62a1ca]
[runnervmkj6or:04602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83cc62a28b]
[runnervmkj6or:04602] [11] plumed(+0x15365)[0x55c387f06365]
[runnervmkj6or:04602] *** End of error message ***
</pre>
{% endraw %}

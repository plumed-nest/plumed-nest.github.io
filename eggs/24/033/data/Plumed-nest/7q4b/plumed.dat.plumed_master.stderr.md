**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[fv-az1046-619:05323] *** Process received signal ***
[fv-az1046-619:05323] Signal: Aborted (6)
[fv-az1046-619:05323] Signal code:  (-6)
[fv-az1046-619:05323] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2270045330]
[fv-az1046-619:05323] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f227009eb2c]
[fv-az1046-619:05323] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f227004527e]
[fv-az1046-619:05323] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f22700288ff]
[fv-az1046-619:05323] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f22704a5ff5]
[fv-az1046-619:05323] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f22704bb0da]
[fv-az1046-619:05323] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f22704a5a55]
[fv-az1046-619:05323] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f22704a5a6f]
[fv-az1046-619:05323] [ 8] plumed_master(+0x146dd)[0x55c1f0d7b6dd]
[fv-az1046-619:05323] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f227002a1ca]
[fv-az1046-619:05323] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f227002a28b]
[fv-az1046-619:05323] [11] plumed_master(+0x15365)[0x55c1f0d7c365]
[fv-az1046-619:05323] *** End of error message ***
</pre>
{% endraw %}

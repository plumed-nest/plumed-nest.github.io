**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[fv-az1046-619:05305] *** Process received signal ***
[fv-az1046-619:05305] Signal: Aborted (6)
[fv-az1046-619:05305] Signal code:  (-6)
[fv-az1046-619:05305] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f049f645330]
[fv-az1046-619:05305] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f049f69eb2c]
[fv-az1046-619:05305] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f049f64527e]
[fv-az1046-619:05305] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f049f6288ff]
[fv-az1046-619:05305] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f049faa5ff5]
[fv-az1046-619:05305] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f049fabb0da]
[fv-az1046-619:05305] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f049faa5a55]
[fv-az1046-619:05305] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f049faa5a6f]
[fv-az1046-619:05305] [ 8] plumed(+0x146dd)[0x55db4dd9d6dd]
[fv-az1046-619:05305] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f049f62a1ca]
[fv-az1046-619:05305] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f049f62a28b]
[fv-az1046-619:05305] [11] plumed(+0x15365)[0x55db4dd9e365]
[fv-az1046-619:05305] *** End of error message ***
</pre>
{% endraw %}

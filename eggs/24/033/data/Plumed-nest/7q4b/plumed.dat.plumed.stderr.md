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
[fv-az1921-959:60953] *** Process received signal ***
[fv-az1921-959:60953] Signal: Aborted (6)
[fv-az1921-959:60953] Signal code:  (-6)
[fv-az1921-959:60953] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbd9ea45330]
[fv-az1921-959:60953] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbd9ea9eb2c]
[fv-az1921-959:60953] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbd9ea4527e]
[fv-az1921-959:60953] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbd9ea288ff]
[fv-az1921-959:60953] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbd9eea5ff5]
[fv-az1921-959:60953] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbd9eebb0da]
[fv-az1921-959:60953] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbd9eea5a55]
[fv-az1921-959:60953] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbd9eea5a6f]
[fv-az1921-959:60953] [ 8] plumed(+0x146dd)[0x55bbd9e946dd]
[fv-az1921-959:60953] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbd9ea2a1ca]
[fv-az1921-959:60953] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbd9ea2a28b]
[fv-az1921-959:60953] [11] plumed(+0x15365)[0x55bbd9e95365]
[fv-az1921-959:60953] *** End of error message ***
</pre>
{% endraw %}

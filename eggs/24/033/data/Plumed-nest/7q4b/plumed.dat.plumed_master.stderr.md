**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[fv-az1267-279:60333] *** Process received signal ***
[fv-az1267-279:60333] Signal: Aborted (6)
[fv-az1267-279:60333] Signal code:  (-6)
[fv-az1267-279:60333] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3ade445330]
[fv-az1267-279:60333] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3ade49eb2c]
[fv-az1267-279:60333] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3ade44527e]
[fv-az1267-279:60333] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3ade4288ff]
[fv-az1267-279:60333] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3ade8a5ff5]
[fv-az1267-279:60333] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3ade8bb0da]
[fv-az1267-279:60333] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3ade8a5a55]
[fv-az1267-279:60333] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3ade8a5a6f]
[fv-az1267-279:60333] [ 8] plumed_master(+0x146dd)[0x559bd013d6dd]
[fv-az1267-279:60333] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3ade42a1ca]
[fv-az1267-279:60333] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3ade42a28b]
[fv-az1267-279:60333] [11] plumed_master(+0x15365)[0x559bd013e365]
[fv-az1267-279:60333] *** End of error message ***
</pre>
{% endraw %}

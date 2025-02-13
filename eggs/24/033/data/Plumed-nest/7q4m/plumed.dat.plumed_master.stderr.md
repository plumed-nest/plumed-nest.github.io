**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[fv-az1046-619:05472] *** Process received signal ***
[fv-az1046-619:05472] Signal: Aborted (6)
[fv-az1046-619:05472] Signal code:  (-6)
[fv-az1046-619:05472] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4f51a45330]
[fv-az1046-619:05472] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4f51a9eb2c]
[fv-az1046-619:05472] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4f51a4527e]
[fv-az1046-619:05472] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4f51a288ff]
[fv-az1046-619:05472] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4f51ea5ff5]
[fv-az1046-619:05472] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4f51ebb0da]
[fv-az1046-619:05472] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4f51ea5a55]
[fv-az1046-619:05472] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4f51ea5a6f]
[fv-az1046-619:05472] [ 8] plumed_master(+0x146dd)[0x556bbb2bc6dd]
[fv-az1046-619:05472] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4f51a2a1ca]
[fv-az1046-619:05472] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4f51a2a28b]
[fv-az1046-619:05472] [11] plumed_master(+0x15365)[0x556bbb2bd365]
[fv-az1046-619:05472] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[fv-az789-879:62343] *** Process received signal ***
[fv-az789-879:62343] Signal: Aborted (6)
[fv-az789-879:62343] Signal code:  (-6)
[fv-az789-879:62343] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc926045330]
[fv-az789-879:62343] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc92609eb2c]
[fv-az789-879:62343] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc92604527e]
[fv-az789-879:62343] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9260288ff]
[fv-az789-879:62343] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc9264a5ff5]
[fv-az789-879:62343] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc9264bb0da]
[fv-az789-879:62343] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc9264a5a55]
[fv-az789-879:62343] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc9264a5a6f]
[fv-az789-879:62343] [ 8] plumed(+0x146dd)[0x55ac112b46dd]
[fv-az789-879:62343] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc92602a1ca]
[fv-az789-879:62343] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc92602a28b]
[fv-az789-879:62343] [11] plumed(+0x15365)[0x55ac112b5365]
[fv-az789-879:62343] *** End of error message ***
</pre>
{% endraw %}

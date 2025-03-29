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
[fv-az789-879:60916] *** Process received signal ***
[fv-az789-879:60916] Signal: Aborted (6)
[fv-az789-879:60916] Signal code:  (-6)
[fv-az789-879:60916] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6e78a45330]
[fv-az789-879:60916] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6e78a9eb2c]
[fv-az789-879:60916] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6e78a4527e]
[fv-az789-879:60916] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6e78a288ff]
[fv-az789-879:60916] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6e78ea5ff5]
[fv-az789-879:60916] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6e78ebb0da]
[fv-az789-879:60916] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6e78ea5a55]
[fv-az789-879:60916] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6e78ea5a6f]
[fv-az789-879:60916] [ 8] plumed_master(+0x146dd)[0x55a99072b6dd]
[fv-az789-879:60916] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6e78a2a1ca]
[fv-az789-879:60916] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6e78a2a28b]
[fv-az789-879:60916] [11] plumed_master(+0x15365)[0x55a99072c365]
[fv-az789-879:60916] *** End of error message ***
</pre>
{% endraw %}

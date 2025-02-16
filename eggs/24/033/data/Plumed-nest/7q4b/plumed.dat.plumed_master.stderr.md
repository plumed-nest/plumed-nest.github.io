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
[fv-az1665-105:60338] *** Process received signal ***
[fv-az1665-105:60338] Signal: Aborted (6)
[fv-az1665-105:60338] Signal code:  (-6)
[fv-az1665-105:60338] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab66c45330]
[fv-az1665-105:60338] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab66c9eb2c]
[fv-az1665-105:60338] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab66c4527e]
[fv-az1665-105:60338] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab66c288ff]
[fv-az1665-105:60338] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab670a5ff5]
[fv-az1665-105:60338] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab670bb0da]
[fv-az1665-105:60338] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab670a5a55]
[fv-az1665-105:60338] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab670a5a6f]
[fv-az1665-105:60338] [ 8] plumed_master(+0x146dd)[0x55cef0a8b6dd]
[fv-az1665-105:60338] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab66c2a1ca]
[fv-az1665-105:60338] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab66c2a28b]
[fv-az1665-105:60338] [11] plumed_master(+0x15365)[0x55cef0a8c365]
[fv-az1665-105:60338] *** End of error message ***
</pre>
{% endraw %}

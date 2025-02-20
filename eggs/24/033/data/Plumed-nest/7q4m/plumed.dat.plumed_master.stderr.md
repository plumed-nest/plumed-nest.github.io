**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[fv-az1372-996:05509] *** Process received signal ***
[fv-az1372-996:05509] Signal: Aborted (6)
[fv-az1372-996:05509] Signal code:  (-6)
[fv-az1372-996:05509] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f89e9245330]
[fv-az1372-996:05509] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f89e929eb2c]
[fv-az1372-996:05509] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f89e924527e]
[fv-az1372-996:05509] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f89e92288ff]
[fv-az1372-996:05509] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f89e96a5ff5]
[fv-az1372-996:05509] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f89e96bb0da]
[fv-az1372-996:05509] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f89e96a5a55]
[fv-az1372-996:05509] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f89e96a5a6f]
[fv-az1372-996:05509] [ 8] plumed_master(+0x146dd)[0x5556616f46dd]
[fv-az1372-996:05509] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f89e922a1ca]
[fv-az1372-996:05509] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f89e922a28b]
[fv-az1372-996:05509] [11] plumed_master(+0x15365)[0x5556616f5365]
[fv-az1372-996:05509] *** End of error message ***
</pre>
{% endraw %}

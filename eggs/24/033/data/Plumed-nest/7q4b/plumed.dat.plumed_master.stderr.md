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
[fv-az1372-996:05332] *** Process received signal ***
[fv-az1372-996:05332] Signal: Aborted (6)
[fv-az1372-996:05332] Signal code:  (-6)
[fv-az1372-996:05332] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa1d1245330]
[fv-az1372-996:05332] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa1d129eb2c]
[fv-az1372-996:05332] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa1d124527e]
[fv-az1372-996:05332] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1d12288ff]
[fv-az1372-996:05332] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1d16a5ff5]
[fv-az1372-996:05332] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1d16bb0da]
[fv-az1372-996:05332] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1d16a5a55]
[fv-az1372-996:05332] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1d16a5a6f]
[fv-az1372-996:05332] [ 8] plumed_master(+0x146dd)[0x55ddbcadb6dd]
[fv-az1372-996:05332] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa1d122a1ca]
[fv-az1372-996:05332] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa1d122a28b]
[fv-az1372-996:05332] [11] plumed_master(+0x15365)[0x55ddbcadc365]
[fv-az1372-996:05332] *** End of error message ***
</pre>
{% endraw %}

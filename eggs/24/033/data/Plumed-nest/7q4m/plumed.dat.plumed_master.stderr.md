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
[fv-az1680-626:05844] *** Process received signal ***
[fv-az1680-626:05844] Signal: Aborted (6)
[fv-az1680-626:05844] Signal code:  (-6)
[fv-az1680-626:05844] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f53a1045330]
[fv-az1680-626:05844] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f53a109eb2c]
[fv-az1680-626:05844] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f53a104527e]
[fv-az1680-626:05844] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53a10288ff]
[fv-az1680-626:05844] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53a14a5ff5]
[fv-az1680-626:05844] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53a14bb0da]
[fv-az1680-626:05844] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53a14a5a55]
[fv-az1680-626:05844] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53a14a5a6f]
[fv-az1680-626:05844] [ 8] plumed_master(+0x146dd)[0x55e494feb6dd]
[fv-az1680-626:05844] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f53a102a1ca]
[fv-az1680-626:05844] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f53a102a28b]
[fv-az1680-626:05844] [11] plumed_master(+0x15365)[0x55e494fec365]
[fv-az1680-626:05844] *** End of error message ***
</pre>
{% endraw %}

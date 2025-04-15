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
[fv-az1921-959:61181] *** Process received signal ***
[fv-az1921-959:61181] Signal: Aborted (6)
[fv-az1921-959:61181] Signal code:  (-6)
[fv-az1921-959:61181] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f53fa245330]
[fv-az1921-959:61181] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f53fa29eb2c]
[fv-az1921-959:61181] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f53fa24527e]
[fv-az1921-959:61181] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53fa2288ff]
[fv-az1921-959:61181] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53fa6a5ff5]
[fv-az1921-959:61181] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53fa6bb0da]
[fv-az1921-959:61181] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53fa6a5a55]
[fv-az1921-959:61181] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53fa6a5a6f]
[fv-az1921-959:61181] [ 8] plumed_master(+0x146dd)[0x56190d8fe6dd]
[fv-az1921-959:61181] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f53fa22a1ca]
[fv-az1921-959:61181] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f53fa22a28b]
[fv-az1921-959:61181] [11] plumed_master(+0x15365)[0x56190d8ff365]
[fv-az1921-959:61181] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az1983-395:60890] *** Process received signal ***
[fv-az1983-395:60890] Signal: Aborted (6)
[fv-az1983-395:60890] Signal code:  (-6)
[fv-az1983-395:60890] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbd5e845330]
[fv-az1983-395:60890] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbd5e89eb2c]
[fv-az1983-395:60890] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbd5e84527e]
[fv-az1983-395:60890] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbd5e8288ff]
[fv-az1983-395:60890] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbd5eca5ff5]
[fv-az1983-395:60890] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbd5ecbb0da]
[fv-az1983-395:60890] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbd5eca5a55]
[fv-az1983-395:60890] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbd5eca5a6f]
[fv-az1983-395:60890] [ 8] plumed_master(+0x146dd)[0x55fcc35c66dd]
[fv-az1983-395:60890] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbd5e82a1ca]
[fv-az1983-395:60890] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbd5e82a28b]
[fv-az1983-395:60890] [11] plumed_master(+0x15365)[0x55fcc35c7365]
[fv-az1983-395:60890] *** End of error message ***
</pre>
{% endraw %}

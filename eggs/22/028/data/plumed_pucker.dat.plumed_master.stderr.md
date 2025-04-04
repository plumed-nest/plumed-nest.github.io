**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az805-507:09945] *** Process received signal ***
[fv-az805-507:09945] Signal: Aborted (6)
[fv-az805-507:09945] Signal code:  (-6)
[fv-az805-507:09945] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc8ce45330]
[fv-az805-507:09945] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc8ce9eb2c]
[fv-az805-507:09945] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc8ce4527e]
[fv-az805-507:09945] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc8ce288ff]
[fv-az805-507:09945] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc8d2a5ff5]
[fv-az805-507:09945] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc8d2bb0da]
[fv-az805-507:09945] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc8d2a5a55]
[fv-az805-507:09945] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc8d2a5a6f]
[fv-az805-507:09945] [ 8] plumed_master(+0x146dd)[0x55b3997bd6dd]
[fv-az805-507:09945] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc8ce2a1ca]
[fv-az805-507:09945] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc8ce2a28b]
[fv-az805-507:09945] [11] plumed_master(+0x15365)[0x55b3997be365]
[fv-az805-507:09945] *** End of error message ***
</pre>
{% endraw %}

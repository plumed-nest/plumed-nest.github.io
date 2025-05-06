**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az1696-883:64950] *** Process received signal ***
[fv-az1696-883:64950] Signal: Aborted (6)
[fv-az1696-883:64950] Signal code:  (-6)
[fv-az1696-883:64950] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc2c3045330]
[fv-az1696-883:64950] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc2c309eb2c]
[fv-az1696-883:64950] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc2c304527e]
[fv-az1696-883:64950] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2c30288ff]
[fv-az1696-883:64950] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc2c34a5ff5]
[fv-az1696-883:64950] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc2c34bb0da]
[fv-az1696-883:64950] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc2c34a5a55]
[fv-az1696-883:64950] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc2c34a5a6f]
[fv-az1696-883:64950] [ 8] plumed(+0x146dd)[0x55ad2149b6dd]
[fv-az1696-883:64950] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc2c302a1ca]
[fv-az1696-883:64950] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc2c302a28b]
[fv-az1696-883:64950] [11] plumed(+0x15365)[0x55ad2149c365]
[fv-az1696-883:64950] *** End of error message ***
</pre>
{% endraw %}

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
[fv-az1719-82:61879] *** Process received signal ***
[fv-az1719-82:61879] Signal: Aborted (6)
[fv-az1719-82:61879] Signal code:  (-6)
[fv-az1719-82:61879] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6ed5045330]
[fv-az1719-82:61879] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6ed509eb2c]
[fv-az1719-82:61879] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6ed504527e]
[fv-az1719-82:61879] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6ed50288ff]
[fv-az1719-82:61879] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6ed54a5ff5]
[fv-az1719-82:61879] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6ed54bb0da]
[fv-az1719-82:61879] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6ed54a5a55]
[fv-az1719-82:61879] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6ed54a5a6f]
[fv-az1719-82:61879] [ 8] plumed(+0x146dd)[0x558a32dc76dd]
[fv-az1719-82:61879] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6ed502a1ca]
[fv-az1719-82:61879] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6ed502a28b]
[fv-az1719-82:61879] [11] plumed(+0x15365)[0x558a32dc8365]
[fv-az1719-82:61879] *** End of error message ***
</pre>
{% endraw %}

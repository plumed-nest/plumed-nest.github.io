**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1701-508:66615] *** Process received signal ***
[fv-az1701-508:66615] Signal: Aborted (6)
[fv-az1701-508:66615] Signal code:  (-6)
[fv-az1701-508:66615] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff8fa445330]
[fv-az1701-508:66615] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff8fa49eb2c]
[fv-az1701-508:66615] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff8fa44527e]
[fv-az1701-508:66615] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff8fa4288ff]
[fv-az1701-508:66615] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff8fa8a5ff5]
[fv-az1701-508:66615] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff8fa8bb0da]
[fv-az1701-508:66615] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff8fa8a5a55]
[fv-az1701-508:66615] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff8fa8a5a6f]
[fv-az1701-508:66615] [ 8] plumed_master(+0x146dd)[0x558c11d9f6dd]
[fv-az1701-508:66615] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff8fa42a1ca]
[fv-az1701-508:66615] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff8fa42a28b]
[fv-az1701-508:66615] [11] plumed_master(+0x15365)[0x558c11da0365]
[fv-az1701-508:66615] *** End of error message ***
</pre>
{% endraw %}

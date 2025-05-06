**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1696-883:68028] *** Process received signal ***
[fv-az1696-883:68028] Signal: Aborted (6)
[fv-az1696-883:68028] Signal code:  (-6)
[fv-az1696-883:68028] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f06de645330]
[fv-az1696-883:68028] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f06de69eb2c]
[fv-az1696-883:68028] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f06de64527e]
[fv-az1696-883:68028] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06de6288ff]
[fv-az1696-883:68028] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06deaa5ff5]
[fv-az1696-883:68028] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06deabb0da]
[fv-az1696-883:68028] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06deaa5a55]
[fv-az1696-883:68028] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06deaa5a6f]
[fv-az1696-883:68028] [ 8] plumed_master(+0x146dd)[0x55f56d9ff6dd]
[fv-az1696-883:68028] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f06de62a1ca]
[fv-az1696-883:68028] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f06de62a28b]
[fv-az1696-883:68028] [11] plumed_master(+0x15365)[0x55f56da00365]
[fv-az1696-883:68028] *** End of error message ***
</pre>
{% endraw %}

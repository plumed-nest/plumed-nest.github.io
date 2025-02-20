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
[fv-az797-511:07072] *** Process received signal ***
[fv-az797-511:07072] Signal: Aborted (6)
[fv-az797-511:07072] Signal code:  (-6)
[fv-az797-511:07072] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f168b645330]
[fv-az797-511:07072] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f168b69eb2c]
[fv-az797-511:07072] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f168b64527e]
[fv-az797-511:07072] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f168b6288ff]
[fv-az797-511:07072] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f168baa5ff5]
[fv-az797-511:07072] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f168babb0da]
[fv-az797-511:07072] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f168baa5a55]
[fv-az797-511:07072] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f168baa5a6f]
[fv-az797-511:07072] [ 8] plumed(+0x146dd)[0x561b9a4fc6dd]
[fv-az797-511:07072] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f168b62a1ca]
[fv-az797-511:07072] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f168b62a28b]
[fv-az797-511:07072] [11] plumed(+0x15365)[0x561b9a4fd365]
[fv-az797-511:07072] *** End of error message ***
</pre>
{% endraw %}

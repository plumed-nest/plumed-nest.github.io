**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az2035-366:12106] *** Process received signal ***
[fv-az2035-366:12106] Signal: Aborted (6)
[fv-az2035-366:12106] Signal code:  (-6)
[fv-az2035-366:12106] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6043045330]
[fv-az2035-366:12106] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f604309eb2c]
[fv-az2035-366:12106] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f604304527e]
[fv-az2035-366:12106] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f60430288ff]
[fv-az2035-366:12106] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f60434a5ff5]
[fv-az2035-366:12106] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f60434bb0da]
[fv-az2035-366:12106] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f60434a5a55]
[fv-az2035-366:12106] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f60434a5a6f]
[fv-az2035-366:12106] [ 8] plumed_master(+0x146dd)[0x563f5e9f16dd]
[fv-az2035-366:12106] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f604302a1ca]
[fv-az2035-366:12106] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f604302a28b]
[fv-az2035-366:12106] [11] plumed_master(+0x15365)[0x563f5e9f2365]
[fv-az2035-366:12106] *** End of error message ***
</pre>
{% endraw %}

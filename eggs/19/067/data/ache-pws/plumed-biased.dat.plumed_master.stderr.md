**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az2035-366:12183] *** Process received signal ***
[fv-az2035-366:12183] Signal: Aborted (6)
[fv-az2035-366:12183] Signal code:  (-6)
[fv-az2035-366:12183] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca79445330]
[fv-az2035-366:12183] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca7949eb2c]
[fv-az2035-366:12183] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca7944527e]
[fv-az2035-366:12183] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca794288ff]
[fv-az2035-366:12183] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca798a5ff5]
[fv-az2035-366:12183] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca798bb0da]
[fv-az2035-366:12183] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca798a5a55]
[fv-az2035-366:12183] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca798a5a6f]
[fv-az2035-366:12183] [ 8] plumed_master(+0x146dd)[0x55b37cd9e6dd]
[fv-az2035-366:12183] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca7942a1ca]
[fv-az2035-366:12183] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca7942a28b]
[fv-az2035-366:12183] [11] plumed_master(+0x15365)[0x55b37cd9f365]
[fv-az2035-366:12183] *** End of error message ***
</pre>
{% endraw %}

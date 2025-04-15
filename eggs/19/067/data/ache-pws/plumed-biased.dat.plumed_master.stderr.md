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
[fv-az1910-428:67754] *** Process received signal ***
[fv-az1910-428:67754] Signal: Aborted (6)
[fv-az1910-428:67754] Signal code:  (-6)
[fv-az1910-428:67754] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd25f845330]
[fv-az1910-428:67754] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd25f89eb2c]
[fv-az1910-428:67754] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd25f84527e]
[fv-az1910-428:67754] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd25f8288ff]
[fv-az1910-428:67754] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd25fca5ff5]
[fv-az1910-428:67754] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd25fcbb0da]
[fv-az1910-428:67754] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd25fca5a55]
[fv-az1910-428:67754] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd25fca5a6f]
[fv-az1910-428:67754] [ 8] plumed_master(+0x146dd)[0x56228b2d76dd]
[fv-az1910-428:67754] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd25f82a1ca]
[fv-az1910-428:67754] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd25f82a28b]
[fv-az1910-428:67754] [11] plumed_master(+0x15365)[0x56228b2d8365]
[fv-az1910-428:67754] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmbietmlfzoi:65505] *** Process received signal ***
[pkrvmbietmlfzoi:65505] Signal: Aborted (6)
[pkrvmbietmlfzoi:65505] Signal code:  (-6)
[pkrvmbietmlfzoi:65505] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0a1da45330]
[pkrvmbietmlfzoi:65505] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0a1da9eb2c]
[pkrvmbietmlfzoi:65505] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0a1da4527e]
[pkrvmbietmlfzoi:65505] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0a1da288ff]
[pkrvmbietmlfzoi:65505] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0a1dea5ff5]
[pkrvmbietmlfzoi:65505] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0a1debb0da]
[pkrvmbietmlfzoi:65505] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0a1dea5a55]
[pkrvmbietmlfzoi:65505] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0a1dea5a6f]
[pkrvmbietmlfzoi:65505] [ 8] plumed(+0x146dd)[0x56123bbfe6dd]
[pkrvmbietmlfzoi:65505] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0a1da2a1ca]
[pkrvmbietmlfzoi:65505] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0a1da2a28b]
[pkrvmbietmlfzoi:65505] [11] plumed(+0x15365)[0x56123bbff365]
[pkrvmbietmlfzoi:65505] *** End of error message ***
</pre>
{% endraw %}

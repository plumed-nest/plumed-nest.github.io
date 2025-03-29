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
[fv-az789-879:61930] *** Process received signal ***
[fv-az789-879:61930] Signal: Aborted (6)
[fv-az789-879:61930] Signal code:  (-6)
[fv-az789-879:61930] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4591045330]
[fv-az789-879:61930] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f459109eb2c]
[fv-az789-879:61930] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f459104527e]
[fv-az789-879:61930] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45910288ff]
[fv-az789-879:61930] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45914a5ff5]
[fv-az789-879:61930] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45914bb0da]
[fv-az789-879:61930] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45914a5a55]
[fv-az789-879:61930] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45914a5a6f]
[fv-az789-879:61930] [ 8] plumed_master(+0x146dd)[0x56121634b6dd]
[fv-az789-879:61930] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f459102a1ca]
[fv-az789-879:61930] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f459102a28b]
[fv-az789-879:61930] [11] plumed_master(+0x15365)[0x56121634c365]
[fv-az789-879:61930] *** End of error message ***
</pre>
{% endraw %}

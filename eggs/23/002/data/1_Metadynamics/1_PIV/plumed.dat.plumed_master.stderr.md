**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1267-279:64261] *** Process received signal ***
[fv-az1267-279:64261] Signal: Aborted (6)
[fv-az1267-279:64261] Signal code:  (-6)
[fv-az1267-279:64261] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd893645330]
[fv-az1267-279:64261] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd89369eb2c]
[fv-az1267-279:64261] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd89364527e]
[fv-az1267-279:64261] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8936288ff]
[fv-az1267-279:64261] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd893aa5ff5]
[fv-az1267-279:64261] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd893abb0da]
[fv-az1267-279:64261] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd893aa5a55]
[fv-az1267-279:64261] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd893aa5a6f]
[fv-az1267-279:64261] [ 8] plumed_master(+0x146dd)[0x562ee1e906dd]
[fv-az1267-279:64261] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd89362a1ca]
[fv-az1267-279:64261] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd89362a28b]
[fv-az1267-279:64261] [11] plumed_master(+0x15365)[0x562ee1e91365]
[fv-az1267-279:64261] *** End of error message ***
</pre>
{% endraw %}

**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1267-279:64317] *** Process received signal ***
[fv-az1267-279:64317] Signal: Aborted (6)
[fv-az1267-279:64317] Signal code:  (-6)
[fv-az1267-279:64317] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7f99a45330]
[fv-az1267-279:64317] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7f99a9eb2c]
[fv-az1267-279:64317] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7f99a4527e]
[fv-az1267-279:64317] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7f99a288ff]
[fv-az1267-279:64317] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7f99ea5ff5]
[fv-az1267-279:64317] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7f99ebb0da]
[fv-az1267-279:64317] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7f99ea5a55]
[fv-az1267-279:64317] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7f99ea5a6f]
[fv-az1267-279:64317] [ 8] plumed_master(+0x146dd)[0x5556056e06dd]
[fv-az1267-279:64317] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7f99a2a1ca]
[fv-az1267-279:64317] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7f99a2a28b]
[fv-az1267-279:64317] [11] plumed_master(+0x15365)[0x5556056e1365]
[fv-az1267-279:64317] *** End of error message ***
</pre>
{% endraw %}

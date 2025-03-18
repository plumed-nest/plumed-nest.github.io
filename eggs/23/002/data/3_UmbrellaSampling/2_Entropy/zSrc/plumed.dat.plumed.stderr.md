**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1267-279:64563] *** Process received signal ***
[fv-az1267-279:64563] Signal: Aborted (6)
[fv-az1267-279:64563] Signal code:  (-6)
[fv-az1267-279:64563] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f9a045330]
[fv-az1267-279:64563] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f9a09eb2c]
[fv-az1267-279:64563] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f9a04527e]
[fv-az1267-279:64563] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f9a0288ff]
[fv-az1267-279:64563] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f9a4a5ff5]
[fv-az1267-279:64563] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f9a4bb0da]
[fv-az1267-279:64563] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f9a4a5a55]
[fv-az1267-279:64563] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f9a4a5a6f]
[fv-az1267-279:64563] [ 8] plumed(+0x146dd)[0x562f17c096dd]
[fv-az1267-279:64563] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f9a02a1ca]
[fv-az1267-279:64563] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f9a02a28b]
[fv-az1267-279:64563] [11] plumed(+0x15365)[0x562f17c0a365]
[fv-az1267-279:64563] *** End of error message ***
</pre>
{% endraw %}

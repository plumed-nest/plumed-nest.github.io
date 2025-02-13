**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1665-105:07894] *** Process received signal ***
[fv-az1665-105:07894] Signal: Aborted (6)
[fv-az1665-105:07894] Signal code:  (-6)
[fv-az1665-105:07894] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9600045330]
[fv-az1665-105:07894] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f960009eb2c]
[fv-az1665-105:07894] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f960004527e]
[fv-az1665-105:07894] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96000288ff]
[fv-az1665-105:07894] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f96004a5ff5]
[fv-az1665-105:07894] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f96004bb0da]
[fv-az1665-105:07894] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f96004a5a55]
[fv-az1665-105:07894] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f96004a5a6f]
[fv-az1665-105:07894] [ 8] plumed_master(+0x146dd)[0x55f33ab986dd]
[fv-az1665-105:07894] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f960002a1ca]
[fv-az1665-105:07894] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f960002a28b]
[fv-az1665-105:07894] [11] plumed_master(+0x15365)[0x55f33ab99365]
[fv-az1665-105:07894] *** End of error message ***
</pre>
{% endraw %}

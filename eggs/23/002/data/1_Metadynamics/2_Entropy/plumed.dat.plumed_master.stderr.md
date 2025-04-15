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
[fv-az1921-959:64156] *** Process received signal ***
[fv-az1921-959:64156] Signal: Aborted (6)
[fv-az1921-959:64156] Signal code:  (-6)
[fv-az1921-959:64156] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2245045330]
[fv-az1921-959:64156] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f224509eb2c]
[fv-az1921-959:64156] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f224504527e]
[fv-az1921-959:64156] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f22450288ff]
[fv-az1921-959:64156] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f22454a5ff5]
[fv-az1921-959:64156] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f22454bb0da]
[fv-az1921-959:64156] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f22454a5a55]
[fv-az1921-959:64156] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f22454a5a6f]
[fv-az1921-959:64156] [ 8] plumed_master(+0x146dd)[0x561d3f5016dd]
[fv-az1921-959:64156] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f224502a1ca]
[fv-az1921-959:64156] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f224502a28b]
[fv-az1921-959:64156] [11] plumed_master(+0x15365)[0x561d3f502365]
[fv-az1921-959:64156] *** End of error message ***
</pre>
{% endraw %}

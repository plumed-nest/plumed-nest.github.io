**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1665-105:07843] *** Process received signal ***
[fv-az1665-105:07843] Signal: Aborted (6)
[fv-az1665-105:07843] Signal code:  (-6)
[fv-az1665-105:07843] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd18fe45330]
[fv-az1665-105:07843] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd18fe9eb2c]
[fv-az1665-105:07843] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd18fe4527e]
[fv-az1665-105:07843] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd18fe288ff]
[fv-az1665-105:07843] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1902a5ff5]
[fv-az1665-105:07843] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1902bb0da]
[fv-az1665-105:07843] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1902a5a55]
[fv-az1665-105:07843] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1902a5a6f]
[fv-az1665-105:07843] [ 8] plumed_master(+0x146dd)[0x5613ace716dd]
[fv-az1665-105:07843] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd18fe2a1ca]
[fv-az1665-105:07843] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd18fe2a28b]
[fv-az1665-105:07843] [11] plumed_master(+0x15365)[0x5613ace72365]
[fv-az1665-105:07843] *** End of error message ***
</pre>
{% endraw %}

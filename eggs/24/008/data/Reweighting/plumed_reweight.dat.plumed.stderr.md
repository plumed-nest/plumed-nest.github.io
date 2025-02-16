**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[fv-az1665-105:60723] *** Process received signal ***
[fv-az1665-105:60723] Signal: Aborted (6)
[fv-az1665-105:60723] Signal code:  (-6)
[fv-az1665-105:60723] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2b84645330]
[fv-az1665-105:60723] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2b8469eb2c]
[fv-az1665-105:60723] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2b8464527e]
[fv-az1665-105:60723] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2b846288ff]
[fv-az1665-105:60723] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2b84aa5ff5]
[fv-az1665-105:60723] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2b84abb0da]
[fv-az1665-105:60723] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2b84aa5a55]
[fv-az1665-105:60723] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2b84aa5a6f]
[fv-az1665-105:60723] [ 8] plumed(+0x146dd)[0x5567a419d6dd]
[fv-az1665-105:60723] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2b8462a1ca]
[fv-az1665-105:60723] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2b8462a28b]
[fv-az1665-105:60723] [11] plumed(+0x15365)[0x5567a419e365]
[fv-az1665-105:60723] *** End of error message ***
</pre>
{% endraw %}
